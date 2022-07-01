---
title: ModernComment
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/moderncomment/
---

## ModernComment class

 Represents a comment on a slide.
 

 
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

## Methods

| Name | Description |
| --- | --- |
| [getShape](getshape)() | Returns a shape associated with the comment. Read-only IShape. |
| [getStatus](getstatus)() | Gets or sets the status of the comment. Read/write ModernCommentStatus. |
| [getTextSelectionLength](gettextselectionlength)() | Gets or sets text selection length in text frame if the comment associated with AutoShape. Read/write int. |
| [getTextSelectionStart](gettextselectionstart)() | Gets or sets starting position of text selection in text frame if the comment associated with AutoShape. Read/write int. |
| [setStatus](setstatus)(byte) | Gets or sets the status of the comment. Read/write ModernCommentStatus. |
| [setTextSelectionLength](settextselectionlength)(int) | Gets or sets text selection length in text frame if the comment associated with AutoShape. Read/write int. |
| [setTextSelectionStart](settextselectionstart)(int) | Gets or sets starting position of text selection in text frame if the comment associated with AutoShape. Read/write int. |
