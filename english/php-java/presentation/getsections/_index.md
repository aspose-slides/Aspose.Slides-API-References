---
title: getSections
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 300
url: /php-java/presentation/getsections/
---

## getSections()  method

 Returns a list of all slides sections that are defined in the presentation.
 Read-only  ISectionCollection.
 

 The following examples shows how to create Sections in a PowerPoint Presentation.
 
```php
  $pres = new Presentation();
  try {
    $defaultSlide = $pres->getSlides()->get_Item(0);
    $newSlide1 = $pres->getSlides()->addEmptySlide($pres->getLayoutSlides()->get_Item(0));
    $newSlide2 = $pres->getSlides()->addEmptySlide($pres->getLayoutSlides()->get_Item(0));
    $newSlide3 = $pres->getSlides()->addEmptySlide($pres->getLayoutSlides()->get_Item(0));
    $newSlide4 = $pres->getSlides()->addEmptySlide($pres->getLayoutSlides()->get_Item(0));
    $section1 = $pres->getSections()->addSection("Section 1", $newSlide1);
    // section1 will be ended at newSlide2 and after it section2 will start
    $section2 = $pres->getSections()->addSection("Section 2", $newSlide3);
    $pres->save("pres-sections.pptx", SaveFormat.Pptx);
    $pres->getSections()->reorderSectionWithSlides($section2, 0);
    $pres->save("pres-sections-moved.pptx", SaveFormat.Pptx);
    $pres->getSections()->removeSectionWithSlides($section2);
    $pres->getSections()->appendEmptySection("Last empty section");
    $pres->save("pres-section-with-empty.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
[SectionCollection](../../sectioncollection)


---


