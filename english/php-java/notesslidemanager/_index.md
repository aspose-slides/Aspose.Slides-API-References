---
title: NotesSlideManager
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/notesslidemanager/
---

## NotesSlideManager class

 Notes slide manager.
 

 The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
 
```php
  // Instantiate a Presentation object that represents a presentation file
  $pres = new Presentation("AccessSlides.pptx");
  try {
    // Add notes to first slide
    $mgr = $pres->getSlides()->get_Item(0)->getNotesSlideManager();
    $noteSlide = $mgr->addNotesSlide();
    $noteSlide->getNotesTextFrame()->setText("Your Notes");
    // Save presentation to disk
    $pres->save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

## Methods

| Name | Description |
| --- | --- |
| [addNotesSlide](addnotesslide)() | Returns the notes slide for the current slide, creating one if there isn't. |
| [getNotesSlide](getnotesslide)() | Returns the notes slide for the current slide. Returns null if slide doesn't have notes slide. Read-only INotesSlide. |
| [removeNotesSlide](removenotesslide)() | Removes notes slide of the current slide. |
