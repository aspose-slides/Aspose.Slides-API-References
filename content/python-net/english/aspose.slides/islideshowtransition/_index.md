---
title: ISlideShowTransition
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/islideshowtransition/
---


ISlideShowTransition class

Represents slide show transition.

The ISlideShowTransition type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [sound](/slides/python-net/aspose.slides/islideshowtransition/sound/) | Returns or sets the embedded audio data.<br/>            Read-write :py:class:`aspose.slides.IAudio`. |
| [sound_mode](/slides/python-net/aspose.slides/islideshowtransition/sound_mode/) | Set or returns sound mode for slide transition.<br/>            Read-write :py:enum:`aspose.slides.slideshow.TransitionSoundMode`. |
| [sound_loop](/slides/python-net/aspose.slides/islideshowtransition/sound_loop/) | This attribute specifies if the sound will loop until the next sound event occurs in<br/>            slideshow.<br/>            Read-write :py:class:`bool`. |
| [advance_on_click](/slides/python-net/aspose.slides/islideshowtransition/advance_on_click/) | Specifies whether a mouse click will advance the slide or not. If this attribute is not<br/>            specified then a value of true is assumed.<br/>            Read-write :py:class:`bool`. |
| [advance_after](/slides/python-net/aspose.slides/islideshowtransition/advance_after/) | This attribute specifies if the slideshow will move to the next slide after a certain time.<br/>            Read/write :py:class:`bool`. |
| [advance_after_time](/slides/python-net/aspose.slides/islideshowtransition/advance_after_time/) | Specifies the time, in milliseconds, after which the transition should start. This setting<br/>            may be used in conjunction with the advClick attribute. If this attribute is not specified<br/>            then it is assumed that no auto-advance will occur.<br/>            Read-write :py:class:`int`. |
| [speed](/slides/python-net/aspose.slides/islideshowtransition/speed/) | Specifies the transition speed that is to be used when transitioning from the current slide<br/>            to the next.<br/>            Read-write :py:enum:`aspose.slides.slideshow.TransitionSpeed`. |
| [value](/slides/python-net/aspose.slides/islideshowtransition/value/) | Slide show transition value.<br/>            Read-only :py:class:`aspose.slides.slideshow.ITransitionValueBase`. |
| [type](/slides/python-net/aspose.slides/islideshowtransition/type/) | Type of transition.<br/>            Read-write :py:enum:`aspose.slides.slideshow.TransitionType`. |
| [sound_is_built_in](/slides/python-net/aspose.slides/islideshowtransition/sound_is_built_in/) | Specifies whether or not this sound is a built-in sound. If this attribute is set to true then<br/>            the generating application is alerted to check the name attribute specified for this sound<br/>            in it's list of built-in sounds and can then surface a custom name or UI as needed.<br/>            Read-write :py:class:`bool`. |
| [sound_name](/slides/python-net/aspose.slides/islideshowtransition/sound_name/) | Specifies a human readable name for the sound of the transition. The :py:attr:`aspose.slides.ISlideShowTransition.sound` property must be assigned to get or set the sound name.<br/>            Read-write :py:class:`System.String`. |

