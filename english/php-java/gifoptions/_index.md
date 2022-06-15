---
title: GifOptions
type: docs
weight: 0
url: /php-java/gifoptions/
---

# GifOptions class

 Represents GIF exporting options.
 

## Constructors

| name | description |
| --- | --- |
| [GifOptions](/slides/php-java/gifoptions/gifoptions/)() | Initializes a new instance of the GifOptions class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getDefaultDelay](/slides/php-java/gifoptions/getdefaultdelay/)() | int | Gets or sets default delay time [ms]. This value will be used if ( ISlideShowTransition#getAdvanceAfterTime/ ISlideShowTransition#setAdvanceAfterTime(long)) is not set. The default value is 1000. |
| [getExportHiddenSlides](/slides/php-java/gifoptions/getexporthiddenslides/)() | boolean | Determines whether hidden slides will be exported. The default value is false. |
| [getFrameSize](/slides/php-java/gifoptions/getframesize/)() | Dimension | Gets or sets frame size. If the size is empty then the value will be taken from ( IPresentation#getSlideSize) |
| [getTransitionFps](/slides/php-java/gifoptions/gettransitionfps/)() | int | Gets or sets transition FPS [frames/sec] The default value is 25. |
| [setDefaultDelay](/slides/php-java/gifoptions/setdefaultdelay/)(int) | void | Gets or sets default delay time [ms]. This value will be used if ( ISlideShowTransition#getAdvanceAfterTime/ ISlideShowTransition#setAdvanceAfterTime(long)) is not set. The default value is 1000. |
| [setExportHiddenSlides](/slides/php-java/gifoptions/setexporthiddenslides/)(boolean) | void | Determines whether hidden slides will be exported. The default value is false. |
| [setFrameSize](/slides/php-java/gifoptions/setframesize/)(Dimension) | void | Gets or sets frame size. If the size is empty then the value will be taken from ( IPresentation#getSlideSize) |
| [setTransitionFps](/slides/php-java/gifoptions/settransitionfps/)(int) | void | Gets or sets transition FPS [frames/sec] The default value is 25. |
