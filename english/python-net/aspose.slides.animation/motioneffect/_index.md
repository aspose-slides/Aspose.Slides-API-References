---
title: MotionEffect
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
weight: 370
url: /python-net/aspose.slides.animation/motioneffect/
---

## MotionEffect class

Represent motion effect behavior of effect.

The MotionEffect type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|MotionEffect()|Initializes a new instance of the MotionEffect class|
## Properties
| Name | Description |
| :- | :- |
|accumulate|Represents whether animation behaviors are accumulated.<br/>            Read/write [NullableBool](/slides/python-net/aspose.slides/nullablebool/).|
|additive|Represents whether the current animation behavior is combined with other running animations.<br/>            Read/write [BehaviorAdditiveType](/slides/python-net/aspose.slides.animation/behavioradditivetype/).|
|properties|Represents properties of behavior.<br/>            Read-only [IBehaviorPropertyCollection](/slides/python-net/aspose.slides.animation/ibehaviorpropertycollection/).|
|timing|Represents timing properties for the effect behavior.<br/>            Read/write [ITiming](/slides/python-net/aspose.slides.animation/itiming/).|
|from_address|Specifies an x/y co-ordinate to start the animation from (in percents). <br/>            Read/write aspose.pydrawing.PointF.|
|to|Specifies the target location for an animation motion effect (in percents).<br/>            Read/write aspose.pydrawing.PointF.|
|by|Describes the relative offset value for the animation (in percents).<br/>            Read/write aspose.pydrawing.PointF.|
|rotation_center|Describes the center of the rotation used to rotate a motion path by X angle.<br/>            Read/write aspose.pydrawing.PointF.|
|origin|Specifies what the origin of the motion path is relative to such as the layout of the slide,<br/>            or the parent.<br/>            Read/write [MotionOriginType](/slides/python-net/aspose.slides.animation/motionorigintype/).|
|path|Specifies the path primitive followed by coordinates for the animation motion.<br/>            Read/write [IMotionPath](/slides/python-net/aspose.slides.animation/imotionpath/).|
|path_edit_mode|Specifies how the motion path moves when shape is moved.<br/>            Read/write [MotionPathEditMode](/slides/python-net/aspose.slides.animation/motionpatheditmode/).|
|angle|Describes the relative angle of the motion path.<br/>            Read/write|
|as_i_behavior|Allows to get base IBehavior interface.<br/>            Read-only [IBehavior](/slides/python-net/aspose.slides.animation/ibehavior/).|

### See Also

* namespace [aspose.slides.animation](/slides/python-net/aspose.slides.animation/)
* assembly [Aspose.Slides](/slides/python-net/)

