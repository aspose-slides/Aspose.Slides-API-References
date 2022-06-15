---
title: RenderingOptions
type: docs
weight: 0
url: /php-java/renderingoptions/
---

# RenderingOptions class

 Provides options that control how a presentation/slide is rendered.
 

 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $renderingOpts = new RenderingOptions();
    $renderingOpts->getNotesCommentsLayouting()->setNotesPosition(NotesPositions.BottomTruncated);
    ImageIO->write($pres->getSlides()->get_Item(0)->getThumbnail($renderingOpts), "PNG", new File("pres-Original.png"));
    $renderingOpts->setDefaultRegularFont("Arial Black");
    ImageIO->write($pres->getSlides()->get_Item(0)->getThumbnail($renderingOpts), "PNG", new File("pres-ArialBlackDefault.png"));
    $renderingOpts->setDefaultRegularFont("Arial Narrow");
    ImageIO->write($pres->getSlides()->get_Item(0)->getThumbnail($renderingOpts), "PNG", new File("pres-ArialNarrowDefault.png"));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

## Constructors

| name | description |
| --- | --- |
| [RenderingOptions](/slides/php-java/renderingoptions/renderingoptions/)() | Default constructor. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getNotesCommentsLayouting](/slides/php-java/renderingoptions/getnotescommentslayouting/)() | INotesCommentsLayoutingOptions | Provides options that control how notes and comments is placed in exported document. |
