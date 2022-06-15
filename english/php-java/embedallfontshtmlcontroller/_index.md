---
title: EmbedAllFontsHtmlController
type: docs
weight: 0
url: /php-java/embedallfontshtmlcontroller/
---

# EmbedAllFontsHtmlController class

 The formatting controller class to use for embedding all presentation fonts in WOFF format.
 

## Constructors

| name | description |
| --- | --- |
| [EmbedAllFontsHtmlController](/php-java/embedallfontshtmlcontroller/embedallfontshtmlcontroller/)() | Creates new instance |
| [EmbedAllFontsHtmlController](/php-java/embedallfontshtmlcontroller/embedallfontshtmlcontroller/)(java.lang.String[]) | Creates new instance |

## Methods

| name | return type | description |
| --- | --- | --- |
| [writeAllFonts](/php-java/embedallfontshtmlcontroller/writeallfonts/)(IHtmlGenerator, IPresentation) | void | Write all fonts contained in Presentation. |
| [writeDocumentEnd](/php-java/embedallfontshtmlcontroller/writedocumentend/)(IHtmlGenerator, IPresentation) | void | Called to write html document footer. Called once per presentation conversion. |
| [writeDocumentStart](/php-java/embedallfontshtmlcontroller/writedocumentstart/)(IHtmlGenerator, IPresentation) | void | Called to write html document header. Called once per presentation conversion. |
| [writeFont](/php-java/embedallfontshtmlcontroller/writefont/)(IHtmlGenerator, IFontData, IFontData, String, String, byte[]) | void | Writes data as base64 into HTML document itself |
| [writeShapeEnd](/php-java/embedallfontshtmlcontroller/writeshapeend/)(IHtmlGenerator, IShape) | void | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |
| [writeShapeStart](/php-java/embedallfontshtmlcontroller/writeshapestart/)(IHtmlGenerator, IShape) | void | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |
| [writeSlideEnd](/php-java/embedallfontshtmlcontroller/writeslideend/)(IHtmlGenerator, ISlide) | void | Called to write html slide footer. Called once per each of slides. |
| [writeSlideStart](/php-java/embedallfontshtmlcontroller/writeslidestart/)(IHtmlGenerator, ISlide) | void | Called to write html slide header. Called once per each of slides. |
