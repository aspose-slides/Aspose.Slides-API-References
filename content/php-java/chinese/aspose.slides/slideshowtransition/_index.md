---
title: SlideShowTransition
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/slideshowtransition/
---
## SlideShowTransition 类

 表示幻灯片放映过渡。

### equals {#equals}

| 名称 | 描述 |
| --- | --- |
| equals (Object) | 确定两个 SlideShowTransition 实例是否相等。读/写 boolean。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| obj | Object | 用于与当前 SlideShowTransition 比较的 SlideShowTransition。 |

 **返回:**
boolean


---


### getAdvanceAfter {#getAdvanceAfter}

| 名称 | 描述 |
| --- | --- |
| getAdvanceAfter () | 此属性指定幻灯片放映是否在一定时间后移动到下一张幻灯片。读/写 boolean。 |

 **返回:**
boolean


---


### getAdvanceAfterTime {#getAdvanceAfterTime}

| 名称 | 描述 |
| --- | --- |
| getAdvanceAfterTime () | 指定在毫秒为单位的时间，之后应开始过渡。此设置可与 advClick 属性一起使用。如果未指定此属性，则假定不会自动前进。读/写 long。 |

 **返回:**
long


---


### getAdvanceOnClick {#getAdvanceOnClick}

| 名称 | 描述 |
| --- | --- |
| getAdvanceOnClick () | 指定鼠标点击是否会前进幻灯片。如果未指定此属性，则假定其值为 true。读/写 boolean。 |

 **返回:**
boolean


---


### getDuration {#getDuration}

| 名称 | 描述 |
| --- | --- |
| getDuration () | 获取或设置幻灯片过渡效果的持续时间（毫秒）。读/写 int。对应于 PresentationML 架构中 p:transition 元素的 p14:dur 属性。如果未设置，则持续时间将根据 #getSpeed/ #setSpeed(int) 属性和过渡类型自动确定。 |

 **返回:**
int


---


### getSound {#getSound}

| 名称 | 描述 |
| --- | --- |
| getSound () | 获取或设置嵌入的音频数据。读/写 IAudio。 |

 **返回:**
[Audio](../audio)


---


### getSoundIsBuiltIn {#getSoundIsBuiltIn}

| 名称 | 描述 |
| --- | --- |
| getSoundIsBuiltIn () | 指定此声音是否为内置声音。如果此属性设置为 true，则生成应用程序会被提示检查其内置声音列表中为此声音指定的 name 属性，并可根据需要显示自定义名称或 UI。读/写 boolean。 |

 **返回:**
boolean


---


### getSoundLoop {#getSoundLoop}

| 名称 | 描述 |
| --- | --- |
| getSoundLoop () | 此属性指定声音是否会循环播放，直至幻灯片放映中出现下一个声音事件。读/写 boolean。 |

 **返回:**
boolean


---


### getSoundMode {#getSoundMode}

| 名称 | 描述 |
| --- | --- |
| getSoundMode () | 设置或获取幻灯片过渡的声音模式。读/写 TransitionSoundMode。 |

 **返回:**
int


---


### getSoundName {#getSoundName}

| 名称 | 描述 |
| --- | --- |
| getSoundName () | 指定转场声音的可读名称。必须为 Sound( #getSound/ #setSound(IAudio)) 属性赋值，才能获取或设置声音名称。读/写 String。 |

 **返回:**
String

 **异常**

| 错误 | 条件 |
| --- | --- |
| PptxException | 当未赋值 {@code Sound}( #getSound/ #setSound(IAudio)) 属性时。此名称在手动配置转场声音时出现在 PowerPoint 用户界面中。 |


---


### getSpeed {#getSpeed}

| 名称 | 描述 |
| --- | --- |
| getSpeed () | 指定从当前幻灯片过渡到下一张幻灯片时使用的过渡速度。读/写 TransitionSpeed。 |

 **返回:**
int


---


### getType {#getType}

| 名称 | 描述 |
| --- | --- |
| getType () | 过渡类型。读/写 TransitionType。 |

 **返回:**
int


---


### getValue {#getValue}

| 名称 | 描述 |
| --- | --- |
| getValue () | 幻灯片放映过渡值。只读 ITransitionValueBase。 |

 **返回:**
[OrientationTransition](../orientationtransition), [OptionalBlackTransition](../optionalblacktransition), [FlyThroughTransition](../flythroughtransition), [LeftRightDirectionTransition](../leftrightdirectiontransition), [TransitionValueBase](../transitionvaluebase), [EightDirectionTransition](../eightdirectiontransition), [EmptyTransition](../emptytransition), [RippleTransition](../rippletransition), [WheelTransition](../wheeltransition), [RevealTransition](../revealtransition), [MorphTransition](../morphtransition), [SplitTransition](../splittransition), [InOutTransition](../inouttransition), [GlitterTransition](../glittertransition), [SideDirectionTransition](../sidedirectiontransition), [ShredTransition](../shredtransition), [CornerDirectionTransition](../cornerdirectiontransition)


---


### hashCode {#hashCode}

| 名称 | 描述 |
| --- | --- |
| hashCode () | 用作特定类型的哈希函数，适用于哈希算法和哈希表等数据结构。 |

 **返回:**
int


---


### setAdvanceAfter {#setAdvanceAfter}

| 名称 | 描述 |
| --- | --- |
| setAdvanceAfter (boolean) | 此属性指定幻灯片放映是否在一定时间后移动到下一张幻灯片。读/写 boolean。 |

 **返回:**
void


---


### setAdvanceAfterTime {#setAdvanceAfterTime}

| 名称 | 描述 |
| --- | --- |
| setAdvanceAfterTime (long) | 指定在毫秒为单位的时间，之后应开始过渡。此设置可与 advClick 属性一起使用。如果未指定此属性，则假定不会自动前进。读/写 long。 |

 **返回:**
void


---


### setAdvanceOnClick {#setAdvanceOnClick}

| 名称 | 描述 |
| --- | --- |
| setAdvanceOnClick (boolean) | 指定鼠标点击是否会前进幻灯片。如果未指定此属性，则假定其值为 true。读/写 boolean。 |

 **返回:**
void


---


### setDuration {#setDuration}

| 名称 | 描述 |
| --- | --- |
| setDuration (int) | 获取或设置幻灯片过渡效果的持续时间（毫秒）。读/写 int。对应于 PresentationML 架构中 p:transition 元素的 p14:dur 属性。如果未设置，则持续时间将根据 #getSpeed/ #setSpeed(int) 属性和过渡类型自动确定。 |

 **返回:**
void


---


### setSound {#setSound}

| 名称 | 描述 |
| --- | --- |
| setSound ([Audio](../audio)) | 获取或设置嵌入的音频数据。读/写 IAudio。 |

 **返回:**
void


---


### setSoundIsBuiltIn {#setSoundIsBuiltIn}

| 名称 | 描述 |
| --- | --- |
| setSoundIsBuiltIn (boolean) | 指定此声音是否为内置声音。如果此属性设置为 true，则生成应用程序会被提示检查其内置声音列表中为此声音指定的 name 属性，并可根据需要显示自定义名称或 UI。读/写 boolean。 |

 **返回:**
void


---


### setSoundLoop {#setSoundLoop}

| 名称 | 描述 |
| --- | --- |
| setSoundLoop (boolean) | 此属性指定声音是否会循环播放，直至幻灯片放映中出现下一个声音事件。读/写 boolean。 |

 **返回:**
void


---


### setSoundMode {#setSoundMode}

| 名称 | 描述 |
| --- | --- |
| setSoundMode (int) | 设置或获取幻灯片过渡的声音模式。读/写 TransitionSoundMode。 |

 **返回:**
void


---


### setSoundName {#setSoundName}

| 名称 | 描述 |
| --- | --- |
| setSoundName (String) | 指定转场声音的可读名称。必须为 Sound( #getSound/ #setSound(IAudio)) 属性赋值，才能获取或设置声音名称。读/写 String。 |

 **返回:**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| PptxException | 当未赋值 {@code Sound}( #getSound/ #setSound(IAudio)) 属性时。此名称在手动配置转场声音时出现在 PowerPoint 用户界面中。 |


---


### setSpeed {#setSpeed}

| 名称 | 描述 |
| --- | --- |
| setSpeed (int) | 指定从当前幻灯片过渡到下一张幻灯片时使用的过渡速度。读/写 TransitionSpeed。 |

 **返回:**
void


---


### setType {#setType}

| 名称 | 描述 |
| --- | --- |
| setType (int) | 过渡类型。读/写 TransitionType。 |

 **返回:**
void


---  