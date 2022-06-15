---
title: SwfOptions
type: docs
weight: 0
url: /php-java/swfoptions/
---

# SwfOptions class

 Provides options that control how a presentation is saved in Swf format.
 

## Constructors

| name | description |
| --- | --- |
| [SwfOptions](/php-java/swfoptions/swfoptions/)() | Default constructor. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getCompressed](/php-java/swfoptions/getcompressed/)() | boolean | Specifies whether the generated SWF document should be compressed or not. Default is true. |
| [getEnableContextMenu](/php-java/swfoptions/getenablecontextmenu/)() | boolean | Enable/disable context menu. Default is true. |
| [getJpegQuality](/php-java/swfoptions/getjpegquality/)() | int | Specifies the quality of JPEG images. Default is 95. |
| [getLogoImageBytes](/php-java/swfoptions/getlogoimagebytes/)() | byte | Image that will be displayed as logo in the top right corner of the viewer. Image should be 32x64 pixels PNG image, otherwise logo can be displayed improperly. |
| [getLogoLink](/php-java/swfoptions/getlogolink/)() | String | Gets or sets the full hyperlink address for a logo. Has an effect only if a ( #getLogoImageBytes/ #setLogoImageBytes(byte[])) is specified. |
| [getNotesCommentsLayouting](/php-java/swfoptions/getnotescommentslayouting/)() | INotesCommentsLayoutingOptions | Provides options that control how notes and comments is placed in exported document. |
| [getShowBottomPane](/php-java/swfoptions/getshowbottompane/)() | boolean | Show/hide bottom pane. Can be overridden in flashvars. Default is true. |
| [getShowFullScreen](/php-java/swfoptions/getshowfullscreen/)() | boolean | Show/hide fullscreen button. Can be overridden in flashvars. Default is true. |
| [getShowHiddenSlides](/php-java/swfoptions/getshowhiddenslides/)() | boolean | Specifies whether the generated document should include hidden slides or not. Default is false. |
| [getShowLeftPane](/php-java/swfoptions/getshowleftpane/)() | boolean | Show/hide left pane. Can be overridden in flashvars. Default is true. |
| [getShowPageBorder](/php-java/swfoptions/getshowpageborder/)() | boolean | Specifies whether border around pages should be shown. Default is true. |
| [getShowPageStepper](/php-java/swfoptions/getshowpagestepper/)() | boolean | Show/hide page stepper. Can be overridden in flashvars. Default is true. |
| [getShowSearch](/php-java/swfoptions/getshowsearch/)() | boolean | Show/hide search section. Can be overridden in flashvars. Default is true. |
| [getShowTopPane](/php-java/swfoptions/getshowtoppane/)() | boolean | Show/hide whole top pane. Can be overridden in flashvars. Default is true. |
| [getStartOpenLeftPane](/php-java/swfoptions/getstartopenleftpane/)() | boolean | Start with opened left pane. Can be overridden in flashvars. Default is false. |
| [getViewerIncluded](/php-java/swfoptions/getviewerincluded/)() | boolean | Specifies whether the generated SWF document should include the integrated document viewer or not. Default is true. |
| [setCompressed](/php-java/swfoptions/setcompressed/)(boolean) | void | Specifies whether the generated SWF document should be compressed or not. Default is true. |
| [setEnableContextMenu](/php-java/swfoptions/setenablecontextmenu/)(boolean) | void | Enable/disable context menu. Default is true. |
| [setJpegQuality](/php-java/swfoptions/setjpegquality/)(int) | void | Specifies the quality of JPEG images. Default is 95. |
| [setLogoImageBytes](/php-java/swfoptions/setlogoimagebytes/)(byte[]) | void | Image that will be displayed as logo in the top right corner of the viewer. Image should be 32x64 pixels PNG image, otherwise logo can be displayed improperly. |
| [setLogoLink](/php-java/swfoptions/setlogolink/)(String) | void | Gets or sets the full hyperlink address for a logo. Has an effect only if a ( #getLogoImageBytes/ #setLogoImageBytes(byte[])) is specified. |
| [setShowBottomPane](/php-java/swfoptions/setshowbottompane/)(boolean) | void | Show/hide bottom pane. Can be overridden in flashvars. Default is true. |
| [setShowFullScreen](/php-java/swfoptions/setshowfullscreen/)(boolean) | void | Show/hide fullscreen button. Can be overridden in flashvars. Default is true. |
| [setShowHiddenSlides](/php-java/swfoptions/setshowhiddenslides/)(boolean) | void | Specifies whether the generated document should include hidden slides or not. Default is false. |
| [setShowLeftPane](/php-java/swfoptions/setshowleftpane/)(boolean) | void | Show/hide left pane. Can be overridden in flashvars. Default is true. |
| [setShowPageBorder](/php-java/swfoptions/setshowpageborder/)(boolean) | void | Specifies whether border around pages should be shown. Default is true. |
| [setShowPageStepper](/php-java/swfoptions/setshowpagestepper/)(boolean) | void | Show/hide page stepper. Can be overridden in flashvars. Default is true. |
| [setShowSearch](/php-java/swfoptions/setshowsearch/)(boolean) | void | Show/hide search section. Can be overridden in flashvars. Default is true. |
| [setShowTopPane](/php-java/swfoptions/setshowtoppane/)(boolean) | void | Show/hide whole top pane. Can be overridden in flashvars. Default is true. |
| [setStartOpenLeftPane](/php-java/swfoptions/setstartopenleftpane/)(boolean) | void | Start with opened left pane. Can be overridden in flashvars. Default is false. |
| [setViewerIncluded](/php-java/swfoptions/setviewerincluded/)(boolean) | void | Specifies whether the generated SWF document should include the integrated document viewer or not. Default is true. |
