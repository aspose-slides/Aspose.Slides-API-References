---
title: SlideUtil
type: docs
weight: 0
url: /php-java/slideutil/
---

# SlideUtil class

 Offer methods which help to search shapes and text in a presentation.
 

## Constructors

| name | description |
| --- | --- |
| [SlideUtil](/php-java/slideutil/slideutil/)() |  |

## Methods

| name | return type | description |
| --- | --- | --- |
| [alignShapes](/php-java/slideutil/alignshapes/)(int, boolean, IShapeCollection) | void | Changes the placement of all shapes in the collection. Aligns shapes to the margins or the edge of the slide or align them relative to each other. |
| [alignShapes](/php-java/slideutil/alignshapes/)(int, boolean, IBaseSlide) | void | Changes the placement of all shapes on the slide. Aligns shapes to the margins or the edge of the slide or align them relative to each other. |
| [alignShapes](/php-java/slideutil/alignshapes/)(int, boolean, IBaseSlide, int[]) | void | Changes the placement of selected shapes on the slide. Aligns shapes to the margins or the edge of the slide or align them relative to each other. |
| [alignShapes](/php-java/slideutil/alignshapes/)(int, boolean, IGroupShape) | void | Changes the placement of all shapes within group shape. Aligns shapes to the margins or the edge of the slide or align them relative to each other. |
| [alignShapes](/php-java/slideutil/alignshapes/)(int, boolean, IGroupShape, int[]) | void | Changes the placement of selected shapes within group shape. Aligns shapes to the margins or the edge of the slide or align them relative to each other. |
| [findShape](/php-java/slideutil/findshape/)(IPresentation, String) | IShape | Find shape by alternative text in a PPTX presentation. |
| [findShape](/php-java/slideutil/findshape/)(IBaseSlide, String) | IShape | Find shape by alternative text on a slide in a PPTX presentation. |
| [getAllTextBoxes](/php-java/slideutil/getalltextboxes/)(IBaseSlide) | ITextFrame | Returns all text frames on a slide in a PPTX presentation. |
| [getAllTextFrames](/php-java/slideutil/getalltextframes/)(IPresentation, boolean) | ITextFrame | Returns all text frames in a PPTX presentation. |
