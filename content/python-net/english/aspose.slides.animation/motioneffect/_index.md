---
title: MotionEffect class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.animation/
---


## MotionEffect class

Represent motion effect behavior of effect.

**Inheritance:**[`MotionEffect`](/slides/python-net/aspose.slides.animation/motioneffect) → [`Behavior`](/slides/python-net/aspose.slides.animation/behavior)

The MotionEffect type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.animation/motioneffect/#) |  |

## Properties

| Property | Description |
| :- | :- |
| [accumulate](/slides/python-net/aspose.slides.animation/accumulate) | Represents whether animation behaviors are accumulated.<br/>            Read/write :py:enum:`aspose.slides.NullableBool`. |
| [additive](/slides/python-net/aspose.slides.animation/additive) | Represents whether the current animation behavior is combined with other running animations.<br/>            Read/write :py:enum:`aspose.slides.animation.BehaviorAdditiveType`. |
| [properties](/slides/python-net/aspose.slides.animation/properties) | Represents properties of behavior.<br/>            Read-only :py:class:`aspose.slides.animation.IBehaviorPropertyCollection`. |
| [timing](/slides/python-net/aspose.slides.animation/timing) | Represents timing properties for the effect behavior.<br/>            Read/write :py:class:`aspose.slides.animation.ITiming`. |
| [from_address](/slides/python-net/aspose.slides.animation/from_address) | Specifies an x/y co-ordinate to start the animation from (in percents). <br/>            Read/write :py:class:`aspose.pydrawing.PointF`. |
| [to](/slides/python-net/aspose.slides.animation/to) | Specifies the target location for an animation motion effect (in percents).<br/>            Read/write :py:class:`aspose.pydrawing.PointF`. |
| [by](/slides/python-net/aspose.slides.animation/by) | Describes the relative offset value for the animation (in percents).<br/>            Read/write :py:class:`aspose.pydrawing.PointF`. |
| [rotation_center](/slides/python-net/aspose.slides.animation/rotation_center) | Describes the center of the rotation used to rotate a motion path by X angle.<br/>            Read/write :py:class:`aspose.pydrawing.PointF`. |
| [origin](/slides/python-net/aspose.slides.animation/origin) | Specifies what the origin of the motion path is relative to such as the layout of the slide,<br/>            or the parent.<br/>            Read/write :py:enum:`aspose.slides.animation.MotionOriginType`. |
| [path](/slides/python-net/aspose.slides.animation/path) | Specifies the path primitive followed by coordinates for the animation motion.<br/>            Read/write :py:class:`aspose.slides.animation.IMotionPath`. |
| [path_edit_mode](/slides/python-net/aspose.slides.animation/path_edit_mode) | Specifies how the motion path moves when shape is moved.<br/>            Read/write :py:enum:`aspose.slides.animation.MotionPathEditMode`. |
| [angle](/slides/python-net/aspose.slides.animation/angle) | Describes the relative angle of the motion path.<br/>            Read/write :py:class:`float`. |
| [as_i_behavior](/slides/python-net/aspose.slides.animation/as_i_behavior) |  |

