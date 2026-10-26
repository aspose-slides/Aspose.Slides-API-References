---
title: PresentationPlayer
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/presentationplayer/
---
## PresentationPlayer 类

 Represents the player of animations associated with the  Presentation. 
 
### PresentationPlayer {#PresentationPlayer}

| Name | Description |
| --- | --- |
| PresentationPlayer([PresentationAnimationsGenerator](../presentationanimationsgenerator), double) | 创建 PresentationPlayer 的新实例。 |

 **参数:**

| Name | Type | Description |
| --- | --- | --- |
| generator | [PresentationAnimationsGenerator](../presentationanimationsgenerator) | Presentation 动画生成器 |
| fps | double | 每秒帧数 (FPS) |

 **返回值:**
PresentationPlayer


---


### dispose {#dispose}

| Name | Description |
| --- | --- |
| dispose () | 释放 PresentationPlayer 的实例。 |

 **返回值:**
void


---


### getFrameIndex {#getFrameIndex}

| Name | Description |
| --- | --- |
| getFrameIndex () | 获取帧索引。 |

 **返回值:**
int


---


### setFrameTick {#setFrameTick}

| Name | Description |
| --- | --- |
| setFrameTick ([PresentationPlayer.FrameTick](../presentationplayer.frametick)) | 设置新的帧计时事件。当播放器生成由 PresentationAnimationsGenerator 创建的动画的每一帧时触发。 |

 **参数:**

| Name | Type | Description |
| --- | --- | --- |
| event | [PresentationPlayer.FrameTick](../presentationplayer.frametick) | 帧计时事件。 |

 **返回值:**
void


---