---
title: ModernComment
type: docs
weight: 0
url: /php-java/moderncomment/
---

# ModernComment class

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

| name | return type | description |
| --- | --- | --- |
| [getShape](/slides/php-java/moderncomment/getshape/)() | IShape | Returns a shape associated with the comment. Read-only IShape. |
| [getStatus](/slides/php-java/moderncomment/getstatus/)() | byte | Gets or sets the status of the comment. Read/write ModernCommentStatus. |
| [getTextSelectionLength](/slides/php-java/moderncomment/gettextselectionlength/)() | int | Gets or sets text selection length in text frame if the comment associated with AutoShape. Read/write int. |
| [getTextSelectionStart](/slides/php-java/moderncomment/gettextselectionstart/)() | int | Gets or sets starting position of text selection in text frame if the comment associated with AutoShape. Read/write int. |
| [setStatus](/slides/php-java/moderncomment/setstatus/)(byte) | void | Gets or sets the status of the comment. Read/write ModernCommentStatus. |
| [setTextSelectionLength](/slides/php-java/moderncomment/settextselectionlength/)(int) | void | Gets or sets text selection length in text frame if the comment associated with AutoShape. Read/write int. |
| [setTextSelectionStart](/slides/php-java/moderncomment/settextselectionstart/)(int) | void | Gets or sets starting position of text selection in text frame if the comment associated with AutoShape. Read/write int. |
