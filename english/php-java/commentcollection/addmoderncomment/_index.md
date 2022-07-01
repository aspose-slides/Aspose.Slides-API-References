---
title: addModernComment
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/commentcollection/addmoderncomment/
---

## addModernComment(String text, Slide slide, AudioFrame shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, AutoShape shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, Chart shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, Connector shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, GeometryShape shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, GraphicalObject shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, GroupShape shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, Ink shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, LegacyDiagram shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, OleObjectFrame shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, PictureFrame shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, SectionZoomFrame shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, Shape shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, SmartArt shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, SmartArtShape shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, SummaryZoomFrame shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, SummaryZoomSection shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, Table shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, VideoFrame shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, ZoomFrame shape, Point2D.Float position, Date creationTime)  method
## addModernComment(String text, Slide slide, ZoomObject shape, Point2D.Float position, Date creationTime)  method

 Add new modern comment at the end of a collection.
 

 
```php
  $pres = new Presentation();
  try {
    $newAuthor = $pres->getCommentAuthors()->addAuthor("Some Author", "SA");
    $newAuthor->getComments()->addModernComment("This is modern comment", $pres->getSlides()->get_Item(0), null, new Point2D.Float(100, 100), new Date());
    $pres->save($outPptxFileName, SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| text | Plain text of a new modern comment. |
| slide | Slide in a presentation where to add a new modern comment. |
| shape | Shape on a slide to which a new modern comment is associated. |
| position | Position on a slide where to add a new modern comment. |
| creationTime | Time of a modern comment creation. |

### Returns
Added modern comment.


---


