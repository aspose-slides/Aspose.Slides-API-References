---
title: SwfOptions
second_title: Aspose.Sildes for .NET API Reference
description: Provides options that control how a presentation is saved in Swf format.
type: docs
weight: 4320
url: /aspose.slides.export/swfoptions/
---

## SwfOptions class

Provides options that control how a presentation is saved in Swf format.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SwfOptions](swfoptions)() | Default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Specifies whether the generated SWF document should be compressed or not. Default is `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Returns or sets font used in case source font is not found. Read-write String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Enable/disable context menu. Default is true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Returns or sets the visual style of the gradient. Read/write [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Specifies the quality of JPEG images. Default is 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Image that will be displayed as logo in the top right corner of the viewer. Image should be 32x64 pixels PNG image, otherwise logo can be displayed improperly. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Gets or sets the full hyperlink address for a logo. Has an effect only if a [`LogoImageBytes`](./logoimagebytes) is specified. |
| [NotesCommentsLayouting](../../aspose.slides.export/swfoptions/notescommentslayouting) { get; } | Provides options that control how notes and comments is placed in exported document. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Represents a callback object for saving progress updates in percentage. See [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Show/hide bottom pane. Can be overridden in flashvars. Default is true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Show/hide fullscreen button. Can be overridden in flashvars. Default is true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Specifies whether the generated document should include hidden slides or not. Default is `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Show/hide left pane. Can be overridden in flashvars. Default is true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Specifies whether border around pages should be shown. Default is true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Show/hide page stepper. Can be overridden in flashvars. Default is true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Show/hide search section. Can be overridden in flashvars. Default is true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Show/hide whole top pane. Can be overridden in flashvars. Default is true. |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Start with opened left pane. Can be overridden in flashvars. Default is false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Specifies whether the generated SWF document should include the integrated document viewer or not. Default is `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Examples

The following example shows how to convert PowerPoint to SWF Flash.

```csharp
[C#]
// Instantiate a Presentation object that represents a presentation file
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Saving presentation and notes pages
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### See Also

* class [SaveOptions](../saveoptions)
* interface [ISwfOptions](../iswfoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
