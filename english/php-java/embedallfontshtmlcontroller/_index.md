---
title: EmbedAllFontsHtmlController
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/embedallfontshtmlcontroller/
---

## EmbedAllFontsHtmlController class

 The formatting controller class to use for embedding all presentation fonts in WOFF format.
 

## Constructors

| Name | Description |
| --- | --- |
| [EmbedAllFontsHtmlController](embedallfontshtmlcontroller)() | Creates new instance |
| [EmbedAllFontsHtmlController](embedallfontshtmlcontroller)(java.lang.String[]) | Creates new instance |

## Methods

| Name | Description |
| --- | --- |
| [writeAllFonts](writeallfonts)(IHtmlGenerator, IPresentation) | Write all fonts contained in Presentation. |
| [writeDocumentEnd](writedocumentend)(IHtmlGenerator, IPresentation) | Called to write html document footer. Called once per presentation conversion. |
| [writeDocumentStart](writedocumentstart)(IHtmlGenerator, IPresentation) | Called to write html document header. Called once per presentation conversion. |
| [writeFont](writefont)(IHtmlGenerator, IFontData, IFontData, String, String, byte[]) | Writes data as base64 into HTML document itself |
| [writeShapeEnd](writeshapeend)(IHtmlGenerator, IShape) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |
| [writeShapeStart](writeshapestart)(IHtmlGenerator, IShape) | Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous. |
| [writeSlideEnd](writeslideend)(IHtmlGenerator, ISlide) | Called to write html slide footer. Called once per each of slides. |
| [writeSlideStart](writeslidestart)(IHtmlGenerator, ISlide) | Called to write html slide header. Called once per each of slides. |
