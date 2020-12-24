> 该材料是OGC，而且是被OGL的条款许可公开使用的。

# 战斗

战斗是循环的，每个人都在一个正常轮组成的循环中轮流行动。战斗按照以下顺序进行：

1. 每个作战者开始时都处于`措手不及`（flat-footed）状态。作战者行动以后，则不再处于措手不及状态。
2. GM决定哪些作战者在作战开始时觉察到他们的敌人。如果只有一部分作战者觉察到敌人，那么在作战的`正常轮`（regular round）开始前有一个突袭轮（surprise round）。觉察到敌人的作战者可以在突袭轮中行动，因此他们要投一个先攻。按照先攻顺序（高骰点先），每个觉察到敌人的作战者可以在突袭轮中做一个`动作`（移动或攻击）。那些没觉察到敌人的作战者在突袭轮中不能做动作。如果在战斗开始时没有人觉察到对方，或者所有人都彼此发现，那么没有突袭轮。
3. 还没有投过先攻的作战者投先攻。现在所有的作战者都将开始进行第一个正常轮。
4. 作战者按先攻顺序行动。
5. 当所有人都过了一轮后，先攻最高的作战者再次行动，并且重复步骤4和5直到作战结束。

## 战斗数据

这一部分列举了战斗所需的基本数据。

## 攻击骰

攻击骰代表角色在自己的一个回合中试图攻击对手的行为。角色做一个攻击骰，即投1d20再加上角色的攻击加值。若结果大于等于对方的防御值，则角色命中并造成伤害。许多调整值也会作用于攻击骰。

投1（d20结果为1）在攻击骰中直接判定为失手。投20（d20结果为20）直接判定命中。投出20点`自然骰`一定会造成威胁——可以打出重击。

若角色不擅长其使用的武器（无相应的擅长专长），角色的攻击骰要受4点减值。

## 攻击加值

角色使用近战武器的攻击加值为：

基础攻击加值 + 力量调整值 + 体型调整值

角色使用远程武器的攻击加值为：

基础攻击加值 + 敏捷调整值 + 体型调整值

### 力量调整值

力量让角色能更快更有力地挥舞武器，所以角色的力量调整值作用于近战攻击骰。

### 体型调整值

生物的体型与武器及其他物品的尺寸不是一个概念。因为体型调整值也用于对抗近战或远程的防御值计算，所以两个体型相同的生物互相攻击，体型调整值抵消，可不计。生物的体型可与载具的体型是一个概念，将参与对抗计算。

**表：体型调整值**

|体型（范例）|体型调整值|
|--------------|:-----------:|
|超巨型（蓝鲸 \[90 尺长\])|–8|
|巨型 （灰鲸 \[40 尺长\])|–4|
|超大型（大象）|–2|
|大型（狮子）|–1|
|普通（人类）|+0|
|小型（德国牧羊犬）|+1|
|超小型（大家鼠）|+2|
|微型（大鼠）|+4|
|超微型（马蝇）|+8|

### 敏捷调整值

敏捷是身体协调性与稳定性的综合指标，所以角色的敏捷调整值应用于远程攻击骰。

### 距离减值

远程武器攻击骰的距离减值取决于角色使用何种武器和目标有多远。所有远程武器与投掷武器都有`射程跨度`（见表：远程武器与表：近战武器）。距离低于一跨度的任何攻击都不会因射程受到惩罚。超过射程跨度时，每超过一倍射程跨度，攻击骰都要受到2点减值。投掷武器最大射程为射程跨度的5倍。射弹的远程武器的最大射程为射程跨度的10倍

## 伤害

角色以武器成功命中时，将按武器类型结算伤害。对武器伤害的数值修正的`效果`，同样应用于徒手击打和生物的天生武器攻击。

目标的当前生命值将扣除此次造成的伤害值。

### 最低武器伤害

如果因为减值导致伤害值低于1，那么依然可以造成1点伤害。

### 力量加值

当角色使用近战武器或投掷武器命中时，其力量调整值将应用在伤害上。

副手武器（Off-Hand Weapon）： 当用副手武器造成伤害时，只能加上一半的强壮加值。

双手武器：当以双手武器造成伤害时，伤害值可以加上力量加值的1.5倍。但该规则不适用于双手使用一把轻武器；这种情形下，伤害骰只能应用一倍力量加值。

## 伤害倍增

有时候由于种种原因，造成的伤害是倍增的。进行多次伤害掷骰（每次都应用全部调整值）并计算总和。

以额外骰表示的额外伤害不可倍增。造成重击时，额外伤害在此次攻击中不参与倍增。

## 重击

当角色掷攻击骰时，自然骰结果为20点，角色将无视目标的防御值直接命中，并产生一个`重击威胁`。要判断该攻击是否真的是重击，角色需立即再以完全相同的调整值掷一次攻击骰。如果第二次攻击骰与目标的防御值对抗的结果为`命中`，则此次攻击为一次重击。（第二次掷骰是判定是否为重击的，角色不需要再掷出20）如果第二次掷骰结果为失手，则该攻击只是一次普通命中。

重击将使角色的伤害倍增。除非特别说明，倍增值为2。（有的武器可能有更高的倍增值，重击造成更多伤害。）有的武器有更宽的重击威胁区间，造成重击的可能性更高。但即使是这些武器，也只能在自然骰为20时为必然命中。`表：远程武器`和`表：近战武器`的`重击`一列给出了每种武器的重击威胁区间。

造成重击时，以额外骰表示的额外伤害不可倍增。

物品（包括载具）以及一些种类的生物免疫重击。投20仍为必然命中，但无法对这些目标施加倍增的伤害。

## 防御

角色的防御值代表了对方对自己成功施加结实有力的一次打击的难度。对手必须掷出大于等于自身防御值的攻击骰才能造成命中。一般一个没有武装的平民防御值为10。角色的防御值等于：

10 + 敏捷调整值 + 职业加值 + 装备加值 + 体型调整值

### 敏捷调整值

高敏捷意味着角色能熟练地闪避击打和火器射击。低敏捷则意味着角色在这方面十分笨拙。角色的敏捷调整值将应用于防御值。

有时角色无法使用敏捷加值。若角色无法对攻击做出反应则无法在防御中算上敏捷加值。

### 职业加值

角色的职业和等级给角色提供了一个固有的防御加值。这些加值在所有情况下都生效，甚至在角色措手不及或是由于其他原因失去敏捷加值的情况下。

### 装备加值

角色穿着护甲也能提供防御加值。这一加值代表护甲为角色抵挡击打的能力。

护甲为穿戴的角色提供了一个最小装备加值，而擅长或精通特定类型护甲的角色可以获得更高的防御加值。

有时角色无法将装备加值应用于防御。如果一次攻击仅通过接触攻击对角色造成伤害，角色不能算上装备加值（见下文`接触攻击`）。

### 体型调整值

目标的个头越大，在战斗中越容易被击中。越小则越难被击中。因为该调整值也应用于攻击骰，相同体型的生物之间的攻击不会受此影响。体型调整值将在`表：体型调整值`中列出。

### 其他调整值

其他要素也可影响角色的防御值。

专长：有的专长为角色的防御提供加值。

天生护甲：有的生物具有天生护甲，通常为鳞片、毛皮或厚肉。

闪避加值：主动闪避攻击同样会为防御提供加值。这类加值被称为闪避加值。任何敏捷调整值无效的情况，闪避加值同样无效。同大多数加值不同，闪避加值可以相互叠加。

魔法效果：有的冒险可能会加入魔法内容。部分魔法效果能够为护甲提供加成，或是提供偏斜加值以使对方的攻击失效。

### 接触攻击

有的攻击无视护甲。这种情况下，攻击方需要掷一个接触攻击骰（远程接触攻击或近战接触攻击）。攻击方攻击骰照常计算，但防御方的护甲或装备加值不算在内。其他调整值，如职业加值、敏捷调整值和体型调整值照常计算。

## 生命值

角色的生命值表示角色在倒下前还能承受多少伤害。生命值由角色的职业和等级决定，角色的体质调整值共同作用。

角色的生命值降到0，角色瘫痪。降到-1，角色濒死。降到-10，角色死亡。

## 速度

角色的速度表示角色能在一个移动动作中移动多远。人类一般能移动30尺，而一些生物移动得更快或更慢。穿着护甲会减慢角色的移动速度。

角色通常以一个移动动作移动，剩下一个攻击动作。但角色可以把攻击动作当作第二个移动动作使用。这能让角色再次移动，最多可以移动正常速度的两倍距离。此外还可以`全力奔跑`（一个整轮动作）。这可以让角色以四倍的速度移动，但角色一次只能在一条直线上奔跑，而且这么做会影响角色的防御（见`奔跑`）。

## 豁免

通常，当角色受到特殊攻击或魔法攻击时，需要掷一个豁免骰以避免或者减少这种攻击的效果。豁免骰是1d20加上基于角色职业与等级的加值（角色的基础豁免加值）再加上属性调整值。

投1（d20结果为1）在豁免骰中直接判定失败。投20（d20结果为20）直接判定成功。

角色的豁免骰加值为：

基础豁免加值 + 属性调整值

豁免的DC由攻击本身决定。

### 豁免骰类型

三种豁免骰类型为：

强韧豁免： 这一豁免代表角色在重大攻击下屹立不倒的能力和在受到类似毒素和麻痹攻击时保持活力的能力。计算强韧豁免骰需要加上角色的体质调整值。

反射豁免： 这一豁免代表角色闪避重大攻击——如爆炸或车祸——的能力。（当伤害不可避免时，角色可以通过成功的反射豁免只承受一半伤害。）计算反射豁免骰需要加上角色的敏捷调整值。

意志豁免： 这一豁免反映了角色对精神上的影响和控制和许多魔法效果的抵抗能力。计算意志豁免骰需要加上角色的感知调整值。

## 先攻

每一轮，每个作战者都执行某些动作。作战者的先攻检定结果的高低，决定了他们行动顺序的先后。

### 先攻检定

一场战斗开始时，每个作战者都做一个先攻检定。一个先攻检定是一次敏捷检定。每个角色将敏捷调整值应用于骰点，拥有`精通先攻`专长的角色的检定拥有额外的4点加值。GM决出角色的行动顺序，结果从高到低，每个角色依次行动。接下来的所有轮里，角色都依照相同的顺序行动（除非角色采取的行动造成其先攻值的改变：详见`特殊先攻动作`）。如果两个或者更多的作战者有相同的先攻值，那么有较高总先攻调整值（包括敏捷调整值和可能有的精通先攻加值）的作战者先行动。如果还是相同，相同的人物再掷一次骰决出他们的先后。

措手不及：战斗开始时，在角色有机会行动前（特别是在角色先攻顺序下的第一回合前），角色是措手不及的。措手不及时，角色不能将敏捷加值应用于防御，也不能做出借机攻击。

### 加入战斗

如果角色进入一场已经开始的战斗，他们将在加入时立即进行一次先攻检定，按检定结果插入队列中，并在轮到自己时行动。

## 突袭

战斗开始时，如果角色未`觉察`到敌人，而敌人觉察到了自己，角色就被`突袭`了。同理，角色如果觉察到敌人而敌人未觉察到角色，角色则可以突袭敌人。

### 突袭轮

如果只有一部分作战者觉察到敌人，那么在作战的`正常轮`（regular round）开始前有一个突袭轮（surprise round）。觉察到敌人的作战者可以在突袭轮中行动，因此他们要投一个先攻。在突袭轮中，按照先攻顺序（高骰点先），每个觉察到敌人的作战者可以在突袭轮中做一个攻击动作或一个移动动作（见下文`动作类型`）。如果没有人觉察到对方，或者所有人都彼此发现，那么没有突袭轮。

### 未觉察的作战者

那些没觉察到敌人的作战者在突袭轮中不能做动作。未觉察的作战者仍是措手不及的，因为他们还没有行动。于是他们在防御中失去所有的敏捷加值。

## 战斗中的动作

基本的移动和攻击动作涵盖了角色在战斗中想要做的大多数行为，如下所述。更细化的选项将在`表：战斗中的动作`介绍，`特殊先攻动作`和`特殊攻击`也有所涉及。

### 战斗轮

每一轮代表游戏世界的6秒钟。每个参与战斗的角色行动一回合便是一轮。角色能在一轮内完成任何现实中一个人在6秒内完成的事。

每轮是从有最高先攻的角色开始的，然后按顺序继续下去。每一轮都使用相同的先攻序列。当轮到角色的回合时，角色能做一轮的时间所能做的动作。（对于例外情况，见`借机攻击`和`特殊先攻动作`。）

对于绝大多数情况，并没有所谓“轮的结束”与“轮的开始”之分。一轮可以是从第一个行动的角色到最后一个行动角色之间的游戏时间，但更多是指从某一个先攻值代表的回合开始到下一轮相同先攻值代表的回合结束的这段时间。持续特定轮数的效果，会在计数达到该特定轮数的轮的首个回合之前结束。

**表：战斗中的动作**

|攻击动作|是否会遭到借机攻击\*|
|--------------|----------------------:|
|攻击（近战）|否|
|攻击（远程）|是|
|攻击（徒手）|是|
|攻击（协助他人）|否|
|冲撞（攻击）|否|
|挣脱擒抱|否|
|虚招（见`唬骗`技能）|否|
|准备（触发一个攻击动作）|否|
|稳定一个濒死角色|是|
|对武器攻击|是|
|对物品攻击|可能\*\*|
|全防御|否|
|使用一个需要攻击动作的技能|通常会|
|开始/完成一个整轮动作|可变|

|移动动作|是否会遭到借机攻击\*|
|------------|----------------------:|
|移动|是|
|使用装备|否|
|攀爬（四分之一速）|否|
|加速攀爬（半速）|是|
|匍匐|否|
|拔出武器\*\*\*|否|
|收回武器|是|
|移动重物|是|
|开门|否|
|捡起物品|是|
|用弹匣或快速装弹器装填|是|
|取出装起来的物品|是|
|从卧、坐、跪的姿态站起|是|
|游泳|否|
|使用一个需要移动动作的技能|通常会|

|整轮动作|是否会遭到借机攻击\*|
|------------------|----------------------:|
|冲撞（冲锋）|否|
|冲锋|否|
|致命一击|是|
|全力攻击|否|
|闯越（冲锋）|否|
|奔跑|是|
|撤退|否|
|扑灭火焰|否|
|使用一个需要整轮动作的技能|通常会|
|装填内置式弹仓的火器|是|

|即时动作|是否会遭到借机攻击\*|
|------------|----------------------:|
|扔掉物品|否|
|向下卧倒、坐、跪|否|
|说话|否|

|可变动作类型|是否会遭到借机攻击\*|
|------------------|----------------------:|
|卸除武器\*\*\*\*|是|
|擒抱\*\*\*\*|是|
|装载武器|是|
|绊摔对手\*\*\*\*|否（若为徒手则是）|
|使用专长\*\*\*\*\*|可变|

|无动作|是否会遭到借机攻击\*|
|---------|----------------------:|
|等待|否|
|五尺快步|否|

\* 不管是什么动作，只要角色移出威胁范围，角色通常都会引发一次借机攻击。该列指的是动作本身是否会引发借机攻击，而非移动部分。

\*\* 如果物品被一个生物拿着、携带着、穿着，则会。否则不会。

\*\*\* 如果角色的基础攻击加值至少有1点，则可以将此动作与一个常规的移动合并。如果角色有`双持`专长，则可以同时拔出两把轻武器或单手武器。

\*\*\*\* 这些攻击类型替代了一次近战攻击，并非动作。因此它们可以像攻击一样在每次攻击或冲锋动作中使用，也可以在全力攻击中一次或多次使用，甚至还可以在借机攻击中使用。

\*\*\*\*\* 效果见对应专长说明。

## 动作类型

有四种动作类型，分别为攻击动作、移动动作、整轮动作和即使动作。在一个正常轮内，角色可以做一个攻击动作和一个移动动作（或两个移动动作；角色总是可以将移动动作代替攻击动作），或者做一个整轮动作。角色也可以做几个即时动作，只要GM允许。

在某些情况下（如在突袭轮中），角色可能被限制只能做一个单独的攻击动作或移动动作。

### 攻击动作

角色可以一个攻击动作做一些事情。角色可以攻击、使用技能或专长（除非技能或专长要求一个整轮动作来执行；见下文），或做其他类似的动作。在一个战斗轮中，角色可以执行一个攻击动作和一个移动动作。角色可以在攻击动作之前或之后做一个移动动作。

### 移动动作

角色可以用一个移动动作进行常速移动，或做需要花费相同时间的类似动作。角色可以以一倍的速度移动、以四分之一的速度攀爬、拔出或收回武器以及其他物品、起立、捡起物品、或做等价于此的动作（见表：战斗中的动作）。

角色可以花费一个攻击动作做一个移动动作。

如果角色在一轮内没有任何移动，角色可以在动作前、动作时、动作后做一个`五尺快步`移动。

### 整轮动作

一个整轮动作将用掉角色一整轮的时间。角色在一个整轮动作中唯一能做的移动行为只有五尺快步，在之前、同时、之后做都行。一些整轮动作不允许角色做五尺快步。角色同时可以在GM的允许下做即时动作（见下文）。

### 即时动作

即时动作只会花费极小的时间和精力，在一轮中，即时动作影响极小所以可以自由地执行。角色在做其他常规动作的同时可以做一到多个即时动作。但GM将对角色真正能做的即时动作做出合理的限制。比如说，扔一件物品、卧倒、说一两句话、全神贯注于施法（如果游戏允许魔法内容）都是即时动作。


## 攻击动作

大多数常见的攻击动作将如下所述。更多具体的攻击动作将在`表：战斗中的动作`中介绍，`特殊攻击`也有所涉及。

### 近战攻击

在持有一般的近战武器时，角色可以攻击5尺内的任意敌人。（5尺内的敌人被视为与角色相邻。）

可做一次以上攻击动作的角色必须使用`全力攻击`动作（见下文`整轮动作`）来执行多次攻击。

防御式战斗：角色在近战时也可采取防御式战斗。如果角色这么做，将在一轮中的攻击骰承受4点减值，以换取在相同轮的防御中获得2点闪避加值。

### 徒手攻击

徒手攻击指用拳打、脚踢、头槌等造成伤害，类似于使用近战武器攻击，区别在于徒手攻击只造成非致命伤害。徒手击打算作用轻近战武器攻击（为了应用双武器惩罚等效果）。徒手攻击应用一般的近战规则，但有如下例外。

借机攻击：对持有武器的对手进行徒手攻击会引发被攻击者的借机攻击。借机攻击会在角色攻击前发生。徒手攻击不会引发第三方的借机攻击，也不会引发徒手对手的借机攻击。

“武装”徒手攻击： 有时角色或生物的徒手攻击仍被视为非徒手攻击（武装攻击）。比如带有爪子、尖牙及类似天生物理武器的生物被视为非徒手。武装是进攻和防御都算的——生物不止在进攻时不会引发武装对手的借机攻击，也在被徒手的对手攻击自己时发动借机攻击。`实战武术`专长可使角色的徒手攻击视为武装攻击。

徒手击打伤害：普通体型角色的徒手击打会造成1d3点（还要像往常一样加上角色的力量调整值）非致命伤害。

角色在掷攻击骰前可指定此次攻击将造成致命伤害，但攻击骰要受到4点减值，因为角色要瞄准致命部位击打。

### Ranged Attacks

With a ranged weapon, a character can shoot or throw at any target that is within the ranged weapon’s maximum range and in line of sight. A target is in line of sight if there are no solid obstructions between the character and the target. The maximum range for a thrown weapon is five range increments. For weapons that fire projectiles, it is ten range increments.

A character capable of making more than one ranged attack per round must use the full attack action (see Full-Round Actions, below) in order to make more than one attack.

Shooting or Throwing into a Melee: If a character shoots or throws a ranged weapon at a target that is engaged in melee with an ally, the character takes a –4 penalty on his or her attack roll be-cause the character has to aim carefully to avoid hitting the ally. Two characters are engaged in melee if they are enemies and they are adjacent to one another. (An unconscious or otherwise immobilized character is not considered engaged unless he or she is actually being attacked.)

If the target is so big that part of it is 10 feet or farther from the nearest ally, the character can avoid the –4 penalty, even if it’s engaged in melee with an ally.

Because of the weapon’s unwieldy shape and size, an attacker using a longarm takes a –4 penalty on attacks against adjacent opponents.

Fighting Defensively: A character can choose to fight defensively while making a ranged attack. 如果角色这么做，将在一轮中的攻击骰承受4点减值，以换取在相同轮的防御中获得2点闪避加值。

### Total Defense

Instead of attacking, a character can use his or her attack action simply to defend. This is called a total defense action. The character doesn’t get to attack or perform any other activity, but does get a +4 dodge bonus to his or her Defense for 1 round. The character’s Defense improves at the start of this action, so it helps against any attacks of opportunity the character is subject to while performing his or her move action.

### Start/Complete Full-Round Action

The “start/complete full-round action” attack action lets a character start undertaking a full-round action (such as those listed on Table: Actions in Combat) at the end of his or her turn, or complete a full-round action by using an attack action at the beginning of his or her turn in the round following the round when the character started the full-round action.

If the character starts a full-round action at the end of his or her turn, the next action that character takes must be to complete the full-round action.

Start/complete full-round action cannot be used with a full attack, charge, run, or withdraw action.

## Move Actions

With the exception of specific movement-related skills, most move actions don’t require a check. In some cases, ability checks might be required.

### Movement

The simplest move action is moving the character’s speed. If a character takes this kind of move action during his or her turn, the character cannot also take a 5-foot step.

Many nonstandard modes of movement are also covered under this category, including climbing and swimming (up to one-quarter the character’s speed), crawling (up to 5 feet), and entering a vehicle.

### Manipulating Objects

In most cases, moving or manipulating an object is a move action. This includes drawing or holstering a weapon, retrieving or putting away a stored object, picking up an object, moving a heavy object, and opening a door.

If the character has a base attack bonus of +1 or higher, he or she can draw a weapon as part of his or her normal movement.

### Standing Up

Standing up from a prone position requires a move action. It provokes an attack of opportunity from opponents who threaten the character.

## Full-Round Actions

A full-round action requires an entire round to complete. If it doesn’t involve moving any distance, a character can combine it with a 5-foot step.

### Charge

Charging is a special full-round action that allows a character to move more than his or her speed and attack during the action. However, there are tight restrictions on how and when a character can charge.

Movement during a Charge: The character must move before his or her attack, not after. The character must move at least 10 feet and may move up to twice his or her speed. All movement must be in a straight line, with no backing up allowed. The character must stop as soon as he or she is within striking range of his or her target (the character can’t run past the target and attack from another direction). A character can’t take a 5-foot step during the same round as a full charge.

During the surprise round (or any other time a character is limited to taking no more than a single attack action on his or her turn) the character can still use the charge action, but he or she is only allowed to move up to his or her speed (instead of up to twice his or her speed).

Attacking after a Charge: After moving, the character may make a single melee attack. The character gets a +2 bonus on the attack roll. The character also takes a –2 penalty to his or her Defense for 1 round (until the beginning of the character’s turn in the following round).

Even if the character has extra attacks, such as from having a high enough base attack bonus or from using multiple weapons, a character only gets to make one attack after a charge.

Instead of attacking the target, a character can attempt to push the target back. See Bull Rush.

### Full Attack

If a character gets more than one attack per action because his or her base attack bonus is high enough, because he or she fights with two weapons, because he or she is using a double weapon, or for some special reason, the character must use the full attack action to get his or her additional attacks. The character does not need to specify the targets of his or her attacks ahead of time. The character can see how the earlier attacks turn out before assigning the later ones.

Full attack is a full-round action. Because of this, the only movement a character can take during a full attack is a 5-foot step. The character may take the step before, after, or between the attacks.

If a character gets multiple attacks based on his or her base attack bonus, the character must make the attacks in order from highest bonus to lowest. If the character is using two weapons, the character can strike with either weapon first. If the character is using a double wea-pon, the character can strike with either part of the weapon first.

Committing to a Full Attack Action: A character doesn’t have to commit to a full attack until after the first attack. The character can then decide whether to make his or her remaining attacks or to take a move action. Of course, if the character has already taken a 5-foot step, he or she can’t use his or her move action to move any distance, but the character could still draw or put away a weapon, for instance (see Move Actions, above).

Fighting Defensively: A character can choose to fight defensively when taking a full attack action. If the character does so, he or she takes a –4 penalty on all attacks in a round to gain a +2 dodge bonus to Defense in the same round.

Attacking with Two Weapons: If the character wields a second weapon in his or her off hand, the character can get one extra attack per round with that weapon. Fighting in this way is very difficult, how-ever—the character takes a –6 penalty on the regular attack or attacks with his or her primary hand and a –10 penalty on the attack with his or her off hand. A character can reduce these penalties in two ways.

1. If the off-hand weapon is light, the penalties are reduced by 2 each. (An unarmed strike is always considered light.)
2. The Two-Weapon Fighting feat lessens the primary hand penalty by 2, and the off-hand penalty by 6.

Table: Two-Weapon Fighting Penalties summarizes the interaction of all these factors.

Double Weapons: A character can use a double weapon to make an extra attack as if he or she were fighting with two weapons. The penalties apply as if the off-hand weapon were light.

**Table: Two-Weapon Fighting Penalties**

|Circumstances|Primary Hand|Off Hand|
|-------------|:----------:|:------:|
|Normal penalties|–6|–10|
|Off-hand weapon is light|–4|–8|
|Two-Weapon Fighting feat|–4|–4|
|Off-hand weapon is light and Two-Weapon Fighting feat|–2|–2|

### 奔跑

A character can run all out as a full-round action. When a character runs, he or she can move up to four times his or her speed in a straight line. (The character does not get a 5-foot step.) The character loses any Dexterity bonus to Defense since he or she can’t avoid attacks. However, the character gets a +2 bonus to Defense against ranged attacks while running.

A character can run for a number of rounds equal to his or her Constitution score, but after that the character must succeed at a Constitution check (DC 10) to continue running. The character must check again each round in which he or she continues to run, and the DC of this check increases by 1 for each check the character makes. When the character fails this check, he or she must stop running. A character who has run to his or her limit must rest for 1 minute (10 rounds) before running again. During a rest period, a character can move normally, but can’t run.

A run represents a speed of about 14 miles per hour for an unencumbered human.

### Withdraw

Withdrawing from melee combat is a full-round action. When a character withdraws, he or she can move up to twice his or her speed. (The character doesn’t also get a 5-foot step.) The square the character starts from is not considered threatened for purposes of withdrawing, and therefore enemies do not get attacks of opportunity against the character when he or she move from that square.

If while withdrawing, the character moves through another threatened square (other than the one started in) without stopping, enemies get attacks of opportunity as normal.

Some forms of movement (such as climbing and swimming) require skill checks from most creatures. A character may not withdraw using a form of movement for which that character must make a skill check.

## Miscellaneous Actions

Some actions don’t fit neatly into the above categories. Some of the options described below are actions that take the place of or are variations on the actions described earlier. For actions not covered in any of this material, the GM determines how long such an action takes to perform and whether doing so provokes attacks of opportunity from threatening enemies.

## Use Feat, Skill, or Talent

Certain feats, let a character take special actions in combat. Other feats are not actions in themselves, but they give a character a bonus when attempting something he or she can already do. Some feats aren’t meant to be used within the framework of combat. The individual feat descriptions tell a character what he or she needs to know about them.

Most uses of skills or talents in a combat situation are attack actions, but some might be move actions or full-round actions. When appropriate, the description of a talent or a skill provides the time required to use it.

## Attacks of Opportunity

The melee combat rules assume that combatants are actively avoiding attacks. A player doesn’t have to declare anything special for his or her character to be on the defensive. Sometimes, however, a combatant in a melee lets his or her guard down, and doesn’t maintain a defensive posture as usual. In this case, combatants near him or her can take advantage of this lapse in defense to attack for free. These attacks are called attacks of opportunity.

### Weapon Type

A character can use a melee weapon to make attacks of opportunity whenever the conditions for such an attack are met (see Provoking an Attack of Opportunity, below). In addition, a character can make attacks of opportunity with unarmed attacks if the character’s unarmed attacks count as armed (see “Armed” Unarmed Attacks).

### Threatened Squares

A character threatens the squares into which he or she can make a melee attack, even when it is not the character’s action. Generally, that’s all squares adjacent to the character’s position. An enemy that takes certain actions while in a threatened square provokes an attack of opportunity from the character. A character can only make attacks of opportunity with melee weapons, never with ranged weapons.

### Provoking an Attack of Opportunity

Two actions can provoke attacks of opportunity: moving out of a threatened square, and performing an action within a threatened square that distracts from defending and lets the character’s guard down.

Moving out of a Threatened Square: When a character moves out of a threatened square, that character generally provokes an attack of opportunity. There are two important exceptions, however. A character doesn’t provoke an attack of opportunity if all he or she moves is a 5-foot step, or if the character withdraws.

If the character doesn’t start in a threatened square, but moves into one, the character has to stop there, or else he or she provokes an attack of opportunity as he or she leaves that square.

Performing an Action that Distracts the Character: Some actions, when performed in a threatened square, provoke attacks of opportunity because they make a character divert his or her attention from the fight at hand. Using a ranged weapon, in particular, provokes attacks of opportunity. Table: Actions in Combat notes many additional actions that provoke attacks of opportunity.

### Making an Attack of Opportunity

An attack of opportunity is a single melee attack, and a character can only make one per round. A character does not have to make an attack of opportunity if he or she doesn’t want to.

An experienced character gets additional regular melee attacks (by using the full attack action), but at a lower attack bonus. A character makes his or her attack of opportunity, however, at his or her normal attack bonus—even if the character has already attacked in this round.

## Movement and Position

When using a grid to represent character’s movement, the standard scale equates 1 inch (or a 1 inch square) to 5 feet in the game world.

### Standard Scale

One inch (or one square) = 5 feet

“Next to” or “adjacent” = 1 inch (5 feet) away

(or in adjacent square)

30mm figure = A human-size creature

A human-size creature occupies an area 1 inch (5 feet) across (or one square)

One round = 6 seconds

### Tactical Movement

Where can a character move, how long it takes to get there, and whether he or she is vulnerable to attacks of opportunity while moving are key questions in combat.

### How Far Can a Character Move?

Humans normally move 30 feet, although armor can slow a character down. Some creatures move faster or slower. A character’s speed when unarmored is sometimes called base speed.

Encumbrance: A character encumbered by carrying a large amount of gear or a fallen comrade may move slower than normal.

Movement in Combat: Generally, a character can move his or her speed as a move action. If a character uses his or her attack action as a move action, the character can move again (for a total movement of up to twice the character’s normal speed). If the character spends the entire round to run all out, he or she can move up to four times his or her normal speed. If a character does something that requires a full round, he or she can only take a 5-foot step.

Movement in Darkness: If a character moves when he or she can’t see, such as in total darkness, his or her speed is limited to one-half normal. The Blind-Fight feat reduces this penalty.

### Passing Through

Sometimes a character can pass through an area occupied by another character or creature.

Friendly Character: A character can move through a square occupied by a friendly character.

Unfriendly Character: There are two ways to move through a square occupied by a resisting enemy. The character can attempt an overrun. Or the character can attempt to tumble through a square occupied by an enemy (if the character has ranks in the Tumble skill; see the skill description).

A character can move through a square occupied by an unfriendly character who doesn’t resist as if the character was friendly.

Square Occupied by Creature Three Sizes Larger or Smaller: Any creature can move through a square occupied by a creature three size categories larger or three categories smaller than it is.

### Flanking

If a character is making a melee attack against an opponent, and an ally directly opposite the character is threatening the opponent, the character and his or her ally flank the opponent. The character gains a +2 bonus on his or her attack roll. The ally must be on the other side of the opponent so that the opponent is directly between the character and the ally.

A character doesn’t gain a bonus for flanking when making a ranged attack.

## Combat Modifiers
This section covers offensive and defensive modifiers provided by position.

### Favorable and Unfavorable Conditions

Generally speaking, any situational modifier created by the attacker’s position or tactics applies to the attack roll, while any situational modifier created by the defender’s position, state, or tactics applies to the defender’s Defense. The GM judges what bonuses and penalties apply, using Table: Defense Modifiers and Table: Attack Roll Modifiers as guides.

**Table: Defense Modifiers**

|Circumstance|Melee|Ranged|
|------------|:---:|:----:|
|Defender sitting or kneeling|–2|+2\*|
|Defender prone|–4|+4\*|
|Defender stunned or cowering|–2\*\*|–2\*\*|
|Defender climbing|–2\*\*|–2\*\*|
|Defender flat-footed|+0\*\*|+0\*\*|
|Defender running|+0\*\*|+2\*\*|
|Defender grappling (attacker not)|+0\*\*|+0\*\*\*|
|Defender pinned|–4\*\*\*\*|+0\*\*\*\*|
|Defender helpless (such as paralyzed, sleeping, or bound)|+0\*\*|+0\*\*|
|Defender has cover|—–— See Cover —–—|
|Defender concealed or invisible|— See Concealment —|

\* Does not apply if target is adjacent to attacker. This circumstance may instead improve bonus to Defense granted by cover. See Cover, below.

\*\* The defender loses any Dexterity bonus to Defense.

\*\*\* Roll randomly to see which grappling combatant the character strikes. That defender loses any Dexterity bonus to Defense.

\*\*\*\* Treat the defender’s Dexterity as 0 (–5 modifier).

**Table: Attack Roll Modifiers**

|Circumstance|Melee|Ranged|
|------------|:---:|:----:|
|Attacker flanking defender\*|+2|—|
|Attacker on higher ground|+1|+0|
|Attacker prone|–4|–2\*\*|
|Attacker invisible|+2\*\*\*|+2\*\*\*|
\* A character flanks a defender when he or she has an ally on the opposite side of the defender threatening the defender.
\*\* Some ranged weapons can’t be used while the attacker is prone.
\*\*\* The defender loses any Dexterity bonus to Defense.

### Cover

Cover provides a bonus to Defense. The more cover a character has, the bigger the bonus. In a melee, if a character has cover against an opponent, that opponent probably has cover against the character, too. With ranged weapons, however, it’s easy to have better cover than the opponent.

The GM may impose other penalties or restrictions on attacks depending on the details of the cover.

### Degree of Cover

Cover is assessed in subjective measurements of how much protection it offers. The GM determines the value of cover. This measure is not a strict mathematical calculation, because a character gains more value from covering the parts of his or her body that are more likely to be struck. If the bottom half of a character’s body is covered, that only gives one-quarter cover, because most vital areas are still fully exposed. If one side or the other of a character’s body is covered, the character gets one-half cover.

### Cover Defense Bonus

Table: Cover gives the Defense bonuses for different degrees of cover. Add the relevant number to the character’s Defense. This cover bonus overlaps (does not stack) with certain other bonuses.

### Cover Reflex Save Bonus

Table: Cover gives the Reflex save bonuses for different degrees of cover. Add this bonus to Reflex saves against attacks that affect an area. This bonus only applies to attacks that originate or burst out from a point on the other side of the cover.

### Striking the Cover Instead of a Missed Target

If it ever becomes important to know whether the cover was actually struck by an incoming attack that misses the intended target, the GM should determine if the attack roll would have hit the protected target without the cover. If the attack roll falls within a range low enough to miss the target with cover but high enough to strike the target if there had been no cover, the object used for cover was struck. This can be particularly important to know in cases when a character uses another character as cover. In such a case, if the cover is struck and the attack roll exceeds the Defense of the covering character, the covering character takes the damage intended for the target.

If the covering character has a Dex-terity bonus to Defense or a dodge bonus, and this bonus keeps the covering character from being hit, then the original target is hit in-stead. The covering character has dodged out of the way and didn’t provide cover after all. A covering character can choose not to apply his or her Dexterity bonus to Defense and/or his or her dodge bonus, if the character so desires.

**Table: Cover**

|Degree of Cover (Example)|Cover Bonus to Defense|Reflex Saves|
|-------------------------|:--------------------:|:----------:|
|One-quarter (standing behind a 3-ft. high wall)|+2|+1|
|One-half (fighting from around a corner or a tree; standing at an open window; behind a creature of same size)|+4|+2|
|Three-quarters (peering around a corner or a big tree)|+7|+3|
|Nine-tenths (standing at an arrow slit; behind a door that’s slightly ajar)|+10|+4\*|
|Total (on the other side of a solid wall)|—|—|

\* Half damage if save is failed; no damage if successful.

### Concealment

Concealment includes all circumstances in which nothing physically blocks a blow or shot, but something interferes with an attacker’s accuracy.

### Degree of Concealment

Concealment is subjectively measured as to how well concealed the defender is. Examples of what might qualify as concealment of various degrees are given in Table: Concealment. Concealment always depends on the point of view of the attacker.

### Concealment Miss Chance

Concealment gives the subject of a successful attack a chance that the attacker missed because of the concealment. If the attacker hits, the defender must make a miss chance percentile roll to avoid being struck. (Actually, it doesn’t matter who makes the roll or whether it’s rolled before or after the attack roll. When multiple concealment conditions apply to a defender, use the one that would produce the highest miss chance. Do not add the miss chances together.

**Table: Concealment**

|Concealment (Example)|Miss Chance|
|---------------------|:---------:|
|One-quarter (light fog; light foliage)|10%|
|One-half (shadows; dense fog at 5 ft.)|20%|
|Three-quarters (dense foliage)|30%|
|Nine-tenths (near total darkness)|40%|
|Total (attacker blind; total darkness; smoke grenade; dense fog at 10 ft.)|50% and must guess target’s location|

## Helpless Defenders

A helpless foe—one who is bound, sleeping, unconscious, or otherwise at the attacker’s mercy—is an easy target. A character can sometimes approach a target who is unaware of his or her presence, get adjacent to the target, and treat him or her as helpless. If the target is in combat or some other tense situation, and therefore in a state of acute awareness and readiness, or if the target can use his or her Dexterity bonus to Defense, then that target can’t be considered unaware. Further, any reasonable precaution taken by a target, including stationing bodyguards, placing his or her back to a wall, or being able to make Spot checks, also precludes catching that target unaware and helpless.

### Regular Attack

A helpless defender has an effective Defense of 5 + his or her size modifier. If a character is attacking with a ranged weapon and is not adjacent to the target, the character can use a full-round action to make the attack, and gain a +5 bonus on the attack roll. If the character is attacking with a melee weapon, or with a ranged weapon from an adjacent square, the character can use a full-round action to deliver a coup de grace.

### Coup de Grace

As a full-round action, a character can use a melee weapon to deliver a coup de grace to a helpless foe. A character can also use a ranged weapon, pro-vided the character is adjacent to the target. The character automatically hits and score a critical hit. If the defender survives the damage, he or she still must make a Fortitude save (DC 10 + damage dealt) or die.

Delivering a coup de grace provokes attacks of opportunity from threatening foes because it involves focused concentration and methodical action.

A character can’t deliver a coup de grace against a creature that is immune to critical hits.

### Knockout Blow

As a full-round action, a character can make an unarmed attack or use a melee weapon that deals nonlethal damage to deliver a knockout blow to a helpless foe. A character can also use a melee weapon that deals lethal damage, but the character takes a –4 penalty on any attempt to deal nonlethal damage with the weapon. The target has an effective Defense of 5 + his or her size modifier. If the character hits, he or she automatically scores a critical hit (see Nonlethal Damage).

Delivering a knockout blow provokes attacks of opportunity from threatening foes because it involves focused concentration and methodical action.

A character can’t deliver a knockout blow against a creature that is immune to critical hits.

## Special Initiative Actions

Usually a character acts as soon as he or she can in combat, but sometimes a character wants to act later, at a better time, or in response to the actions of someone else.

### Delay

By choosing to delay, the character takes no action and then acts normally at whatever point in the initiative count the character decides to act. When a character delays, he or she voluntarily reduces his or her own initiative result for the rest of the combat. When the character’s new, lower initiative count comes up later in the same round, the character can act normally. The character can specify this new initiative result or just wait until some time later in the round and act then, thus fixing the character’s new initiative count at that point.

A character cannot interrupt anyone’s action with a delayed action (as a character can with a readied action; see below).

### Delaying Limits

The longest a character can delay before taking an action is until after everyone else has acted in the round. At that point, the delaying character must act or else forfeit any action in that round.

If multiple characters are delaying, the one with the highest initiative modifier (or highest Dexterity, in case of a tie) has the advantage. If two or more delaying characters both want to act on the same initiative count, the one with the highest initiative modifier gets to go first. If two or more delaying characters are trying to go after one another, the one with the highest initiative modifier gets to go last; the others must go first or lose their action for the round.

If a character loses an action due to delaying, he or she may act on any count on the next turn. Again, the character cannot interrupt an action.

### Ready

The ready action lets a character prepare to take an action later, to interrupt another character. Essentially, the character splits his or her action, taking the move action on the character’s initiative count and the attack action at a later point. On the character’s turn, he or she prepares to take an action later, if a specific trigger is met. Then, later in the round, if the readied action is triggered, the character takes it, acting before the triggering action.

Readying does not provoke an attack of opportunity. (The character’s move action, and the attack action he or she readies, may both provoke attacks of opportunity normally.)

### Readying an Action

A character can ready an attack action or a move action. To do so, the character specifies the action he or she will take and the conditions under which the character will take it.  Then, any time before the character’s next action, the character may take the readied attack action in response to those conditions. The readied action occurs just before the event that triggers it. If the trigger is part of another character’s actions, the readied action interrupts the other character. The other character continues his or her actions once the readied action is completed.

The character’s initiative count changes. For the rest of the encounter, it is the count on which the character took the readied action, and the character acts immediately ahead of the character whose action triggered the readied action.

A character can take a 5-foot step as part of his or her readied action, but only if the character didn’t otherwise move any distance during the round.

If the character comes to his or her next action and has not yet performed the readied action, the character doesn’t get to take the readied action (though the character can ready the same action again). If the character takes his or her readied action in the next round, before his or her regular turn comes up, the character’s initiative count rises to that new point in the order of battle, and he or she does not get your regular action that round.

## Special Attacks

This section covers firearms, grappling, explosives, attacking objects, and an assortment of other special attacks.

## 协助他人

In combat, a character can help a friend attack or defend by distracting or interfering with an opponent. If the character is in position to attack an opponent with which a friend of the character is engaged in melee combat, the character can attempt to aid the friend as an attack action. The character makes an attack roll against Defense 10. If the character succeeds, he or she doesn’t actually damage the opponent—but the character’s friend gains either a +2 circumstance bonus against that opponent or a +2 circumstance bonus to Defense against that opponent (aiding character’s choice) on the friend’s next turn.

## Firearms

The most basic form of attack with a firearm is a single shot. One attack is one pull of the trigger and fires one bullet at one target.

The Personal Firearms Proficiency feat allows a character to make this sort of attack without penalty. If a character isn’t proficient in personal firearms, he or she takes a –4 penalty on attacks with that type of weapon.

A number of other feats allow a character to deal extra damage when he or she fires more than one bullet as part of a single attack at a single target. (If a character doesn’t have those feats, he or she can still fire more than one bullet—but the extra bullets don’t have any effect, and are just wasted ammunition.)

As with all forms of ranged weapons, attacking with a firearm while within a threatened square provokes an attack of opportunity.

Because of the weapon’s unwieldy shape and size, an attacker using a longarm takes a –4 penalty on attacks against adjacent opponents.

### Autofire

If a ranged weapon has an automatic rate of fire, a character may set it on autofire. Autofire affects an area and everyone in it, not a specific creature. The character targets a 10-foot-by-10-foot area and makes an attack roll; the targeted area has an effective Defense of 10. (If the character does not have the Advanced Firearms Proficiency feat, he or she takes a –4 penalty on the attack roll.) If the attack succeeds, every creature within the affected area must make a Reflex save (DC 15) or take the weapon’s damage. Autofire shoots 10 bullets, and can only be used if the weapon has 10 bullets in it.

Autofire is not the same thing as burst fire, which involves firing a short burst at a specific target. Firing a burst requires the Burst Fire feat. If a character fires a blast of automatic fire at a specific target without the Burst Fire feat, it’s treated as a standard attack. The attack, if successful, only deals normal damage—all the extra ammunition the character fired is wasted.

Some firearms—particularly machine guns—only have autofire settings and can’t normally fire single shots.

## Grenades and Explosives

An explosive is a weapon that, when detonated, affects all creatures and objects within its burst radius by means of shrapnel, heat, or massive concussion. Its effect is broad enough that it can hurt characters just by going off close to them.

Some explosives, such as grenades, can be thrown, and they explode when they land. Others are planted, with fuses or timers, and go off after a preset amount of time elapses.

### Thrown Explosives

An attack with a thrown explosive is a ranged attack made against a specific 5-foot square. (A character can target a square occupied by a creature.) Throwing the explosive is an attack action. If the square is within one range increment, you do not need to make an attack roll. Roll 1d4 and consult the table to see which corner of the square the explosive bounces to.

**Thrown Explosives (hit)**

|Roll on d4|Corner of targeted square|
|:--------:|:-----------------------:|
|1|Upper Left|
|2|Upper Right|
|3|Lower Right|
|4|Lower Left|

If the target square is more than one range increment away, make an attack roll. The square has an effective Defense of 10. Thrown weapons require no weapon proficiency, so a character doesn’t take the –4 nonproficient penalty. If the attack succeeds, the grenade or explosive lands in the targeted square. Roll 1d4 and consult the table above to see which corner of the square the explosive bounces to.

If the character misses the target, the explosive lands at a corner of a square nearby in a random direction. Consult the tables below to determine where the explosive lands. If the weapon was thrown two to three range increments (11 to 30 feet), roll 1d8.

**Thrown Explosive (Miss 2 to 3 Range Increments)**

|Roll on d8|Location Struck|
|:--------:|---------------|
|1|upper right corner, one square beyond target|
|2|upper right corner, one square right of target|
|3|lower right corner, one square right of target|
|4|lower right corner, one square short of target|
|5|lower left corner, one square short of target|
|6|lower left corner, one square left of target|
|7|upper left corner, one square left of target|
|8|upper left corner, one square beyond target|

For ranges of up to five range increments (31 to 50 feet), roll 1d12.

**Thrown Explosives (Miss 4 to5 Range Increments)**

|Roll on d12|Location Struck|
|:---------:|---------------|
|1|upper right corner, two squares beyond target|
|2|upper right corner, one square beyond and right of target|
|3|upper right corner, two squares right of target|
|4|lower right corner, two squares right of target|
|5|lower right corner, one square short and right of target|
|6|lower right corner, two squares short of target|
|7|lower left corner, two squares short of target|
|8|lower left corner, one square short and left of target|
|9|lower left corner, two squares left of target|
|10|upper left corner, two squares left of target|
|11|upper left corner, one square beyond and left of target|
|12|upper left corner, two squares beyond target|

After determining where the explosive landed, it deals its damage to all targets within the burst radius of the weapon. The targets may make Reflex saves (DC varies according to the explosive type) for half damage.

### Planted Explosives

A planted explosive is set in place, with a timer or fuse determining when it goes off. No attack roll is necessary to plant an explosive; the explosive sits where it is placed until it is moved or goes off.

When a planted explosive detonates, it deals its damage to all targets within the burst radius of the weapon. The targets may make Reflex saves (DC varies according to the explosive type) for half damage.

## Splash Weapons

A splash weapon is a ranged weapon that breaks apart on impact, splashing or scattering its contents over its target and nearby creatures or objects. Most splash weapons consist of liquids in breakable containers.

To attack with a splash weapon, make a ranged touch attack against the target. Thrown weapons require no weapon proficiency, so characters don’t take the –4 nonproficient penalty. A hit deals direct hit damage to the target and splash damage to all other creatures within 5 feet of the target.

A character can instead target a specific 5-foot square, including a square occupied by a creature. Use the rules for thrown explosives. However, if a character targets a square, creatures within 5 feet are dealt the splash damage, and the direct hit damage is not dealt to any creature.

If the character misses the target (whether aiming at a creature or a square), check to see where the weapon lands, using the rules for thrown explosives.  After determining where the object landed, it deals splash damage to all creatures within 5 feet.

## Attack an Object

Sometimes a character needs to attack or break an object

### Strike an Object

Objects are easier to hit than characters because they usually don’t move, but many are tough enough to shrug off some damage from each blow.

Object Defense and Bonuses to Attack: Objects are harder or easier to hit depending on their size and whether they are immobile or being held, carried, or worn by opponents. The base Defense of objects is shown on Table: Size and Defense of Objects.

**Table: Size and Defense of Objects**

|Size (Example)|Defense|
|--------------|:-----:|
|Colossal (jetliner)|–3|
|Gargantuan (army tank)|1|
|Huge (typical car)|3|
|Large (big door)|4|
|Medium-size (dirt bike)|5|
|Small (chair)|6|
|Tiny (laptop computer)|7|
|Diminutive (paperback book)|9|
|Fine (pencil)|13|


If a character uses a full-round action to make an attack against an inanimate, immobile object, the character gets an automatic hit with a melee weapon, or a +5 bonus on his or her attack roll with a ranged weapon.

An object being held, carried, or worn has a Defense equal to the above figure + 5 + the opponent’s Dexterity modifier + the opponent’s class bonus to Defense. Striking a held, carried, or worn object provokes an attack of opportunity from the character who holds it.  (If a character has the Sunder feat, he or she doesn’t incur an attack of opportunity for making the attempt.)

Hardness: Each object has hardness—a number that represents how well it resists damage. Whenever an object takes damage, subtract its hardness from the damage. Only damage in excess of its hardness is deducted from the object’s hit points (see Table: Substance Hardness and Hit Points and Table: Object Hardness and Hit Points).

Hit Points: An object’s hit point total depends on what it is made of or how big it is (see Table Substance Hardness and Hit Points and Table Object Hardness and Hit Points).

**Table: Substance Hardness and Hit Points**

|Substance|Hardness|Hit Points|
|---------|:------:|----------|
|Paper|0|2/inch of thickness|
|Rope|0|2/inch of thickness|
|Plastic, soft|0|3/inch of thickness|
|Glass|1|1/inch of thickness|
|Ceramic|1|2/inch of thickness|
|Ice|0|3/inch of thickness|
|Plastic, hard|2|5/inch of thickness|
|Wood|5|10/inch of thickness|
|Aluminum|6|10/inch of thickness|
|Concrete|8|15/inch of thickness|
|Steel|10|30/inch of thickness|

**Table: Object Hardness and Hit Points**

|Object|Hardness|Hit Points|Break DC|
|------|:------:|:--------:|:------:|
|Lock||||
|Cheap|0|1|10|
|Average|3|5|15|
|High quality|5|10|20|
|High security|10|120|35|
|Ultrahigh security|20|150|40|
|||||
|Manufactured objects\*||||
|Fine|0|1|10|
|Diminutive|0|1|10|
|Tiny|1|2|10|
|Small|3|3|12|
|Medium-size|5|5|15|
|Large|5|10|15|
|Huge|8|10|20|
|Gargantuan|8|20|30|
|Colossal|10|30|50|
|||||
|Firearm, Medium-size|5|7|17|
|Rope|0|2|23|
|Simple wooden door|5|10|13|
|Strong wooden door|5|20|23|
|Steel door|10|120|35|
|Cinderblock wall|8|90|35|
|Chain|10|5|26|
|Handcuffs|10|10|30|
|Metal bars|10|15|30|

\* Figures for manufactured objects are minimum values. The GM may adjust these upward to account for objects with more strength and durability.

Energy Attacks: Acid and sonic/concussive attacks deal normal damage to most objects. Electricity and fire attacks deal half damage to most objects; divide the damage by 2 before applying the hardness. Cold attacks deal one-quarter damage to most objects; divide the damage by 4 before applying the hardness.

Ineffective Weapons: The GM may determine that certain weapons just can’t deal damage effectively to certain objects.

Immunities: Objects are immune to nonlethal damage and to critical hits.

Saving Throws: Unattended objects never make saving throws. They are considered to have failed their saving throws. An object attended by a character (being grasped, touched, or worn) receives a saving throw just as if the character herself were making the saving throw.

### Breaking Objects

When a character tries to break something with sudden force rather than by dealing damage, use a Strength check to see whether he or she succeeds. The DC depends more on the construction of the object than on the material.

If an object has lost half or more of its hit points, the DC to break it decreases by 2.

### Repairing Objects

Repairing damage to an object takes a full hour of work and appropriate tools. (Without the tools, a character takes a –4 penalty on his or her Repair check.) At the end of the hour, make a Repair check (DC 20). Success restores 2d6 hit points. If damage remains, the character may continue to make repairs for as many hours as it takes to restore all the object’s hit points.

## Bull Rush

A character can attempt a bull rush as an attack action made during his or her move action, or as part of a charge. (In general, a character can’t make an attack action during a move action; this is an exception.) In either case, the character doesn’t get a 5-foot step before, during, or after the bull rush attempt. When the character bull rushes, he or she attempts to push an opponent straight back instead of attacking the opponent. A character can only bull rush an opponent who is one size category larger than the character, the same size, or smaller.

### Initiating a Bull Rush

First, the character moves into the target’s square. Moving in this way provokes an attack of opportunity from each foe that threatens the character, probably including the target.

Second, the character and the target make opposed Strength checks. If the character and the target are different sizes, the larger combatant gets a bonus on the Strength check of +4 per difference in size category. The character gets a +2 bonus if he or she was charging. The target gets a +4 stability bonus if he or she has more than two legs or is otherwise exceptionally stable.

### Bull Rush Results

If the character beats the target’s Strength check, the character pushes the opponent back 5 feet. The character can push the target back an additional 5 feet for every 5 points by which the character exceeded the target’s check result, provided the character moves with the target. A character can’t, however, exceed his or her normal movement for that action. (The target provokes attacks of opportunity if moved. So does the character, if he or she moves with the target. The target and the character do not provoke attacks of opportunity from each other as a result of this movement.)

If the character fails to beat the target’s Strength check, the character moves 5 feet straight back to where the character was before the character moved into the opponents square. If that square is occupied, the character falls prone in the square.

## Overrun

A character can attempt an overrun as an attack action made during his or her move action, or as part of a charge. (In general, a character cannot make an attack action during a move action; this is an exception.) In either case, the character doesn’t get a 5-foot step before, during, or after the overrun attempt. With an overrun, the character attempts to move through an opponents area, going past or over the opponent.  A character can only overrun an opponent who is one size category larger than the character, the same size, or smaller. A character can make only one overrun attempt per action.

First, the character must move at least 10 feet in a straight line into the target’s square (provoking attacks of opportunity normally).

Then the target chooses either to avoid the character or to block the character. If the opponent avoids the character, the character keeps moving. (A character can always move through a square occupied by someone who lets the character by.) If the opponent blocks the character, make a trip attack against the opponent (see Trip). If the character succeeds in tripping his or her opponent, the character can continue his or her movement as normal.

If the character fails and are tripped in turn, the character falls prone in the target’s square. If the character fails but are not tripped, the character has to move 5 feet back the way he or she came, ending his or her movement there. If that square is occupied, the character falls prone in the square.

## Trip

A character can try to trip an opponent, or otherwise knock him or her down, as an unarmed melee attack. A character can only trip an opponent who is one size category larger than the character, the same size, or smaller.

### Making a Trip Attack

Make an unarmed melee touch attack against the target. Doing this provokes an attack of opportunity from the target as normal for unarmed attacks.

If the attack succeeds, make a Strength check opposed by the target’s Dexterity check or Strength check (using whichever ability score has the higher modifier). If the character and the target are different sizes, the larger combatant gets a bonus on the Strength check of +4 per difference in size category. The target gets a +4 stability bonus on his or her check if he or she has more than two legs or is otherwise exceptionally stable. If the character wins, he or she trips the target. If the character loses, the target may immediately react and make a Strength check opposed by the character’s Dexterity check or Strength check to try to trip the character.

### Being Tripped (Prone)

A tripped character is prone (see Table: Defense Modifiers). Standing up from a prone position is a move action.

### Tripping with a Weapon

Some weapons, such as the chain and the whip, can be used to make trip attacks. A character doesn’t incur an attack of opportunity when doing so. If the character is tripped during his or her own trip attempt, the character can drop the weapon to avoid being tripped.

## Disarm

As a melee attack, a character may attempt to disarm his or her opponent. If the character does so with a weapon, he or she knocks the opponent’s weapon out of his or her hands and to the ground. If the character attempt the disarm while unarmed, the character ends up with the weapon in his or her hand.

If a character is attempting to disarm the wielder of a melee weapon, follow the steps outlined here. Disarming the wielder of a ranged weapon is slightly different; see below.

Step One: The character provokes an attack of opportunity from the target he or she is trying to disarm.

Step Two: The character and the target make opposed attack rolls with their respective weapons. If the weapons are different sizes, the combatant with the larger weapon gets a bonus on the attack roll of +4 per difference in size category. If the target is using a weapon in two hands, he or she gets an additional +4 bonus. Also, if the combatants are different sizes, the larger combatant gets a bonus on the attack roll of +4 per difference in size category.

Step Three: If the character beats the target’s attack roll, the target is disarmed. If the character attempted the disarm action unarmed, he or she now has the weapon. If the character was armed, the target’s weapon is on the ground at the target’s feet.

If the character fails the disarm attempt, the target may immediately react and attempt to disarm the character with the same sort of opposed melee attack roll. The opponent’s attempt does not provoke an attack of opportunity from the character. If the opponent fails to disarm, the character does not get a free disarm attempt against the opponent.

### 远程武器

To disarm an opponent wielding a ranged weapon, the character makes a melee attack or unarmed attack to strike the weapon in the opponent’s hand (see Attack an Object). If the weapon is held in two hands, it gets a +2 bonus to its Defense. If the character’s attack succeeds, the ranged weapon falls to the ground or winds up in the character’s hands (if the character made the attack unarmed). This kind of disarm attempt provokes an attack of opportunity, but if the character fails, the target does not get to make a disarm attempt against him or her.

## Grabbing Objects

A character can also use disarm to snatch away an object worn by a target. Doing this works the same as a disarm attempt (see above), except for the following.

Attack of Opportunity: If the target’s attack of opportunity inflicts any damage, the attempt to grab the object automatically fails.

Modifiers: If the object is well secured or otherwise difficult to grab from the target, the target gets a +4 bonus. On the other hand, if the object is poorly secured or otherwise easy to snatch or cut away, the attacker gets a +4 bonus.

Failed Attempts: Failing an attempt to grab an object doesn’t allow the target to at-tempt to disarm the character.

### Grapple

Grappling means wrestling and struggling hand-to-hand.

There are three stages to grappling: grabbing, holding, and pinning.

### Grabbing

Normally, a grab is just the first step to starting a grapple. If the character grabs an opponent, but fails to go on to hold him or her, the character doesn’t actually start a grapple. However, sometimes all a character wants to do is grab the target.

### Holding

Once a character has established a hold, he or she is involved in a grapple. From a hold, a character can attempt a number of actions, including damaging the opponent or pinning the opponent. A character can’t get a hold on any creature more than two size categories larger than the character. (However, such a creature can get a hold on the character—so while a character can’t initiate a grapple with a creature more than two size categories larger than, a character can still end up in one.)

### Pinning

Getting the opponent in a pin is often the goal of a grapple. A pinned character is held immobile.

### Grapple Checks

When a character is involved in a grapple, he or she will need to make opposed grapple checks against an opponent—often repeatedly. A grapple check is something like a melee attack roll. A character’s attack bonus on a grapple check is:

Base attack bonus + Strength modifier + grapple modifier

### Grapple Modifier

A creature’s size works in its favor when grappling, if that creature is Large or larger in size. Conversely, a creature of Small or smaller size is at a disadvantage because of its size when grappling. Instead of using a creature’s size modifier on a grapple check (as would be done for a melee or ranged attack roll), use the appropriate grapple modifier from Table: Grapple Modifiers.

**Table: Grapple Modifiers**

|Size (Example)|Grapple Modifier|
|--------------|:--------------:|
|Colossal (blue whale \[90 ft. long\])|+16|
|Gargantuan (gray whale \[40 ft. long\])|+12|
|Huge (elephant)|+8|
|Large (lion)|+4|
|Medium-size (human)|+0|
|Small (German shepherd)|–4|
|Tiny (housecat)|–8|
|Diminutive (rat)|–12|
|Fine (horsefly)|–16|

### Starting a Grapple

To start a grapple, a character first needs to grab and hold his or her target. Attempting to start a grapple is the equivalent of making a melee attack. If the character gets multiple attacks in a round, he or she can attempt to start a grapple multiple times (at successively lower base attack bonuses). Follow these steps.

1. Attack of Opportunity: A character provokes an attack of opportunity from the target he or she is trying to grapple. If the attack of opportunity deals the character damage, the character fails to start the grapple. If the attack of opportunity misses or otherwise fails to deal damage, proceed to step 2.
2. Grab: The character makes a melee touch attack to grab the target. If the character fails to hit the target, the character fails to start the grapple. If the character succeeds, proceed to step 3.
3. Hold: Make an opposed grapple check. (This is a free action.) If the character succeeds, the character has started the grapple, and deals damage to the target as if with an unarmed strike. If the character loses, he or she fails to start the grapple. The character automatically loses an attempt to hold if the target is two or more size categories larger than the character is (but the character can still make an attempt to grab such a target, if that’s all he or she wants to do).
4. Maintain the Grapple: To maintain the grapple for later rounds, the character must move into the target’s square. (This movement is free and doesn’t count as part of the character’s movement for the round movement.) Moving, as normal, provokes attacks of opportunity from threatening enemies, but not from the target. The character and the target are now grappling. If the character can’t move into the target’s square, the character can’t maintain the grapple and must immediately let go of the target. To grapple again, the character must begin at step 1.

### Grappling Consequences

While a character is grappling, his or her ability to attack others and defend him or herself is limited.

No Threatened Squares: A character doesn’t threaten any squares while grappling.

No Dexterity Bonus: A character loses his or her Dexterity bonus to Defense (if the character has one) against opponents the character isn’t grappling. (The character can still use it against opponents he or she is grappling.)

No Movement: A character cannot move while held in a grapple.

If the Character is Grappling

When a character is grappling (regardless of who started the grapple), he or she can attempt any of several actions on his or her turn. Unless otherwise noted, each of these options is equivalent to an attack. (If the character normally gets more than one attack per attack action, he or she can attempt as many of these options as he or she has attacks available, using his or her successively lower attack bonus for each roll.) The character is limited to these options only; he or she cannot take any other actions.

Damage the Opponent: Make an opposed grapple check; if the character succeeds, he or she deals damage as with an un-armed strike.

Pin: Make an opposed grapple check; if the character succeeds, he or she holds the opponent immobile for 1 round. The opponent takes a –4 penalty to Defense against all attacks from other people (but not from the character); however, the opponent is not considered helpless.

A character can’t use a weapon on a pinned character or attempt to damage or pin a second opponent while holding a pin on the first.

A pinned character can’t take any action except to attempt to escape from the pin.

Escape from Grapple: Make an opposed grapple check. If the character succeeds, he or she can escape the grapple. If more than one opponent is grappling the character, the grapple check result has to beat all their check results to escape. (Opponents don’t have to try to hold a character if they don’t want to.)

Alternatively, the character can make an Escape Artist check opposed by the opponent’s grapple check to escape from the grapple. This is an attack action that the character may only attempt once per round, even if the character gets multiple attacks.

If the character has not used his or her move action for the round, the character may do so after escaping the grapple.

Escape from Pin: Make an opposed grapple check. If the character succeeds, he or she can escape from being pinned. (Opponents don’t have to try to keep the character pinned if they don’t want to.) The character is still being grappled, however.

Alternatively, a character can make an Escape Artist check opposed by the opponent’s grapple check to escape from the pin. This is an attack action that the character may only attempt once per round, even if the character gets multiple attacks.

Break Another’s Pin: Make an opposed grapple check; if the character succeeds, he or she can break the hold that an opponent has over an ally.

Draw a Light Weapon: A character can draw a light weap-on as a move action.

Attack with a Light Weapon: A character can attack with a light weapon while grappling (but not while pinned or pinning). A character can’t attack with two weap-ons while grappling.

### If the Character is Pinned

When an opponent has pinned the character, he or she is held immobile (but not helpless) for 1 round. (the character can’t attempt any other action.) On the character’s turn, he or she can attempt to escape from the pin. If the character succeeds, he or she is still grappling.

### Joining a Grapple

If the target is already grappling someone else, a character can use an attack to start a grapple, as above, except that the target doesn’t get an attack of opportunity against the character, and the character’s grab automatically succeeds. The character still has to make a successful opposed grapple check and move in to be part of the grapple.

If multiple enemies are already involved in the grapple, the character picks one against whom to make the opposed grapple check.

### Multiple Grapplers

Several combatants can be in a single grapple. Up to four combatants can grapple a single opponent in a given round. Creatures that are one size category smaller than the character count as one-half creature each; creatures that are one size category larger than the character count as two creatures; and creatures two or more size categories larger than the character count as four creatures.

When involved in a grapple with multiple opponents, the character chooses one opponent to make an opposed check against. The exception is an attempt to escape from the grapple; to escape, a character’s grapple check must beat the check results of all opponents.
