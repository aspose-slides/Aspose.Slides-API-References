---
title: Aspose.Slides.Animation
second_title: Aspose.Sildes for .NET API Reference
description: Contains classes for work with animation in Microsoft PowerPoint presentations.
type: docs
weight: 20
url: /net/aspose.slides.animation/
---
Contains classes for work with animation in Microsoft PowerPoint presentations.

## Classes

| Class | Description |
| --- | --- |
| class [AnimationTimeLine](./animationtimeline) | Represents timeline of animation. |
| abstract class [Behavior](./behavior) | Represent base class behavior of effect. |
| class [BehaviorCollection](./behaviorcollection) | Represents collection of behavior effects. |
| class [BehaviorFactory](./behaviorfactory) | Allows to create animation effects |
| class [BehaviorProperty](./behaviorproperty) | Represent property types for animation behavior. Follows the list of properties from https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx and https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx |
| class [BehaviorPropertyCollection](./behaviorpropertycollection) | Represents timing properties for the effect behavior. |
| class [ColorEffect](./coloreffect) | Represents a color effect for an animation behavior. |
| class [ColorOffset](./coloroffset) | Represent color offset. |
| class [CommandEffect](./commandeffect) | Represents a command effect for an animation behavior. |
| class [Effect](./effect) | Represents animation effect. |
| class [FilterEffect](./filtereffect) | Represent filter effect of behavior. |
| class [MotionCmdPath](./motioncmdpath) | Represent one command of a path. |
| class [MotionEffect](./motioneffect) | Represent motion effect behavior of effect. |
| class [MotionPath](./motionpath) | Represent motion path. |
| class [Point](./point) | Represent animation point. |
| class [PointCollection](./pointcollection) | Represent collection of animation points. |
| class [PropertyEffect](./propertyeffect) | Represent property effect behavior. |
| class [RotationEffect](./rotationeffect) | Represent rotation behavior of effect. |
| class [ScaleEffect](./scaleeffect) | Represents animation scale effect. |
| class [Sequence](./sequence) | Represents sequence (collection of effects). |
| class [SequenceCollection](./sequencecollection) | Represents collection of interactive sequences. |
| class [SetEffect](./seteffect) | Represents a set effect for an animation behavior. |
| class [TextAnimation](./textanimation) | Represent text animation. |
| class [TextAnimationCollection](./textanimationcollection) | Represents collection of text animations. |
| class [Timing](./timing) | Represents animation timing. |
## Interfaces

| Interface | Description |
| --- | --- |
| interface [IBehavior](./ibehavior) | Represent base class behavior of effect. |
| interface [IBehaviorCollection](./ibehaviorcollection) | Represents collection of behavior effects. |
| interface [IBehaviorFactory](./ibehaviorfactory) | Allows to create animation effects |
| interface [IBehaviorProperty](./ibehaviorproperty) | Represent property types for animation behavior. Follows the list of properties from https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx and https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx |
| interface [IBehaviorPropertyCollection](./ibehaviorpropertycollection) | Represents timing properties for the effect behavior. |
| interface [IColorEffect](./icoloreffect) | Represents a color effect for an animation behavior. |
| interface [IColorOffset](./icoloroffset) | Represent color offset. |
| interface [ICommandEffect](./icommandeffect) | Represents a command effect for an animation behavior. |
| interface [IEffect](./ieffect) | Represents animation effect. |
| interface [IFilterEffect](./ifiltereffect) | Represent filter effect of behavior. |
| interface [IMotionCmdPath](./imotioncmdpath) | Represent one command of a path. |
| interface [IMotionEffect](./imotioneffect) | Represent motion effect behavior of effect. |
| interface [IMotionPath](./imotionpath) | Represent motion path. |
| interface [IPoint](./ipoint) | Represent animation point. |
| interface [IPointCollection](./ipointcollection) | Represents a collection of portions. |
| interface [IPropertyEffect](./ipropertyeffect) | Represent property effect behavior. |
| interface [IRotationEffect](./irotationeffect) | Represent rotation behavior of effect. |
| interface [IScaleEffect](./iscaleeffect) | Represents animation scale effect. |
| interface [ISequence](./isequence) | Represents sequence (collection of effects). |
| interface [ISequenceCollection](./isequencecollection) | Represents collection of interactive sequences. |
| interface [ISetEffect](./iseteffect) | Represents a set effect for an animation behavior. |
| interface [ITextAnimation](./itextanimation) | Represent text animation. |
| interface [ITextAnimationCollection](./itextanimationcollection) | Represents collection of text animations. |
| interface [ITiming](./itiming) | Represents animation timing. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| enum [BehaviorAccumulateType](./behavioraccumulatetype) | Represents types of accumulation of effect behaviors. |
| enum [BehaviorAdditiveType](./behavioradditivetype) | Represents additive type for effect behavior. |
| enum [BuildType](./buildtype) | Determines how text will appear on a shape during animation. |
| enum [ColorDirection](./colordirection) | Represents color direction for color effect behavior. |
| enum [ColorSpace](./colorspace) | Represents color space for color effect behavior. |
| enum [CommandEffectType](./commandeffecttype) | Represents command effect type for command effect behavior. |
| enum [EffectChartMajorGroupingType](./effectchartmajorgroupingtype) | Represents the type of an animation effect for chart's element. |
| enum [EffectChartMinorGroupingType](./effectchartminorgroupingtype) | Represents the type of an animation effect for chart's element in series or category. |
| enum [EffectFillType](./effectfilltype) | Represent fill types. |
| enum [EffectPresetClassType](./effectpresetclasstype) | Represent effect class types. |
| enum [EffectRestartType](./effectrestarttype) | Represent restart types for timing. |
| enum [EffectSubtype](./effectsubtype) | Represents subtypes of animation effect. |
| enum [EffectTriggerType](./effecttriggertype) | Represent trigger type of effect. |
| enum [EffectType](./effecttype) | Represents the type of an animation effect. |
| enum [FilterEffectRevealType](./filtereffectrevealtype) | Represents filter reveal type. |
| enum [FilterEffectSubtype](./filtereffectsubtype) | Represents filter effect subtypes. |
| enum [FilterEffectType](./filtereffecttype) | Represents filter effect types. |
| enum [MotionCommandPathType](./motioncommandpathtype) | Represent types of command for animation motion effect behavior. |
| enum [MotionOriginType](./motionorigintype) | Specifies what the origin of the motion path is relative to. Such as the layout of the slide, or the parent. |
| enum [MotionPathEditMode](./motionpatheditmode) | Specifies how the motion path moves when the target shape is moved |
| enum [MotionPathPointsType](./motionpathpointstype) | Represent types of points in animation motion path. |
| enum [PropertyCalcModeType](./propertycalcmodetype) | Represent calc mode for animation property. |
| enum [PropertyValueType](./propertyvaluetype) | Represent property value types. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
