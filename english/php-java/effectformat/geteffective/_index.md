---
title: getEffective
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 170
url: /php-java/effectformat/geteffective/
---

## getEffective()  method

 Gets effective effect formatting data with the inheritance applied.
 

 This example demonstrates getting some of shape's effective effect properties.
 
```php
  $pres = new Presentation("MyPresentation.pptx");
  try {
    $effectiveEffectFormat = $pres->getSlides()->get_Item(0)->Shapes()->get_Item(0)->getEffectFormat()->getEffective();
    if ($effectiveEffectFormat->isNoEffects()) {
      echo("The shape has not effects applied.");
    } else {
      if ($effectiveEffectFormat->getBlurEffect() != null) {
        echo("Blur effect radius: " + $effectiveEffectFormat->getBlurEffect()->getRadius());
      }
      if ($effectiveEffectFormat->getFillOverlayEffect() != null) {
        echo("Fill overlay effect fill type: " + $effectiveEffectFormat->getFillOverlayEffect()->getFillFormat()->getFillType());
      }
      if ($effectiveEffectFormat->getGlowEffect() != null) {
        echo("Glow effect color: " + $effectiveEffectFormat->getGlowEffect()->getColor());
      }
      if ($effectiveEffectFormat->getInnerShadowEffect() != null) {
        echo("Inner shadow effect shadow color: " + $effectiveEffectFormat->getInnerShadowEffect()->getShadowColor());
      }
      if ($effectiveEffectFormat->getOuterShadowEffect() != null) {
        echo("Outer shadow effect shadow color: " + $effectiveEffectFormat->getOuterShadowEffect()->getShadowColor());
      }
      if ($effectiveEffectFormat->getPresetShadowEffect() != null) {
        echo("Preset shadow effect shadow color: " + $effectiveEffectFormat->getPresetShadowEffect()->getShadowColor());
      }
      if ($effectiveEffectFormat->getReflectionEffect() != null) {
        echo("Reflection effect distance: " + $effectiveEffectFormat->getReflectionEffect()->getDistance());
      }
      if ($effectiveEffectFormat->getSoftEdgeEffect() != null) {
        echo("Soft edge effect radius: " + $effectiveEffectFormat->getSoftEdgeEffect()->getRadius());
      }
    }
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns



---


