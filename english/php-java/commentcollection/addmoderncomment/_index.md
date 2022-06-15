---
title: addModernComment
type: docs
weight: 20
url: /php-java/commentcollection/addmoderncomment/
---

# addModernComment(java.lang.String, com.aspose.slides.ISlide, com.aspose.slides.IShape, java.awt.geom.Point2D.Float, java.util.Date) method

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

##  Parameters

| name | description |
| --- | --- |
| text | Plain text of a new modern comment. |
| slide | Slide in a presentation where to add a new modern comment. |
| shape | Shape on a slide to which a new modern comment is associated. |
| position | Position on a slide where to add a new modern comment. |
| creationTime | Time of a modern comment creation. |

##  Returns
Added modern comment.


