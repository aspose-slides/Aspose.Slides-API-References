---
title: addEffect
type: docs
weight: 10
url: /php-java/sequence/addeffect/
---

# addEffect(com.aspose.slides.IShape, int, int, int) method

 Add new effect to the end of sequence.
 

##  Parameters

| name | description |
| --- | --- |
| shape | Shape object IShape for adding an effect |
| effectType | Type of an animation effect EffectType |
| subtype | Subtypes of animation effect EffectSubtype |
| triggerType | Trigger type of effect EffectTriggerType |

##  Returns
New effect object IEffect


# addEffect(com.aspose.slides.IParagraph, int, int, int) method

  Add new animation effect for paragraph to the end of sequence.
  

  
```php
  $presentation = new Presentation($path + "input.pptx");
  try {
    // select paragraph to add effect
    $autoShape = $presentation->getSlides()->get_Item(0)->getShapes()->get_Item(0);
    $paragraph = $autoShape->getTextFrame()->getParagraphs()->get_Item(0);
    // add Fly animation effect to selected paragraph
    $effect = $presentation->getSlides()->get_Item(0)->getTimeline()->getMainSequence()->addEffect($paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
  } finally {
    if ($presentation != null) {
      $presentation->dispose();
    }
  }
```

##  Parameters

| name | description |
| --- | --- |
| paragraph | Paragraph object IParagraph |
| effectType | Type of an animation effect EffectType |
| subtype | Subtypes of animation effect EffectSubtype |
| triggerType | Trigger type of effect EffectTriggerType |

##  Returns
New effect object IEffect


# addEffect(com.aspose.slides.IChart, int, int, int, int, int) method

 Adds the new chart animation effect for category or series to the end of sequence.
 

##  Parameters

| name | description |
| --- | --- |
| chart | Chart object IChart |
| type | Type of an animation effect EffectChartMinorGroupingType |
| index | Index int |
| effectType | Type of an animation effect EffectType |
| subtype | Subtypes of animation effect EffectSubtype |
| triggerType | Trigger type of effect EffectTriggerType |

##  Returns
New effect object IEffect


# addEffect(com.aspose.slides.IChart, int, int, int, int, int, int) method

 Adds the new chart animation effect for elements in category or series to the end of sequence.
 

##  Parameters

| name | description |
| --- | --- |
| chart | Chart object IChart |
| type | Type of an animation effect EffectChartMinorGroupingType |
| seriesIndex | Index of chart series int |
| categoriesIndex | Index of category int |
| effectType | Type of an animation effect EffectType |
| subtype | Subtypes of animation effect EffectSubtype |
| triggerType | Trigger type of effect EffectTriggerType |

##  Returns
New effect object IEffect


