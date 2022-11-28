---
title: getSubstitutions
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 70
url: /php-java/fontsmanager/getsubstitutions/
---

## getSubstitutions()  method

 Gets the information about fonts that will be replaced on the presentation's rendering.
 

 
```php
  $pres = new Presentation("pres.pptx");
  try {
    for ($fontSubstitution : $pres->getFontsManager()->getSubstitutions()) {
      echo($fontSubstitution->getOriginalFontName() + " ->; " + $fontSubstitution->getSubstitutedFontName());
    }
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
[CommentCollection](../../commentcollection), [LineFormatCollection](../../lineformatcollection), [BehaviorPropertyCollection](../../behaviorpropertycollection), [ColumnCollection](../../columncollection), SortedList, [ChartDataWorksheetCollection](../../chartdataworksheetcollection), [EffectStyleCollection](../../effectstylecollection), [SmartArtNodeCollection](../../smartartnodecollection), [GradientStopCollectionEffectiveData](../../gradientstopcollectioneffectivedata), [DigitalSignatureCollection](../../digitalsignaturecollection), [TabCollection](../../tabcollection), [PieSplitCustomPointCollection](../../piesplitcustompointcollection), [SlideCollection](../../slidecollection), List, [ChartCategoryCollection](../../chartcategorycollection), [SmartArtShapeCollection](../../smartartshapecollection), [ImageTransformOperationCollection](../../imagetransformoperationcollection), [ShapeCollection](../../shapecollection), [FontFallBackRulesCollection](../../fontfallbackrulescollection), SortedDictionary, [Sequence](../../sequence), [RowCollection](../../rowcollection), [SummaryZoomSectionCollection](../../summaryzoomsectioncollection), [ChartSeriesCollection](../../chartseriescollection), LinkedList, Stack, [ChartCellCollection](../../chartcellcollection), [CommentAuthorCollection](../../commentauthorcollection), Collection, [Row](../../row), [AudioCollection](../../audiocollection), [CustomXmlPartCollection](../../customxmlpartcollection), [DataLabelCollection](../../datalabelcollection), Dictionary, [MathBlock](../../mathblock), [TrendlineCollection](../../trendlinecollection), [ImageTransformOCollectionEffectiveData](../../imagetransformocollectioneffectivedata), [ParagraphCollection](../../paragraphcollection), [MasterSlideCollection](../../masterslidecollection), [TextAnimationCollection](../../textanimationcollection), ReadOnlyCollection, [SectionCollection](../../sectioncollection), [MotionPath](../../motionpath), [ChartDataPointCollection](../../chartdatapointcollection), [ControlPropertiesCollection](../../controlpropertiescollection), [FontSubstRuleCollection](../../fontsubstrulecollection), [BehaviorCollection](../../behaviorcollection), [Column](../../column), [VbaReferenceCollection](../../vbareferencecollection), [ImageCollection](../../imagecollection), [PointCollection](../../pointcollection), [MasterLayoutSlideCollection](../../masterlayoutslidecollection), [FillFormatCollection](../../fillformatcollection), [PortionCollection](../../portioncollection), [GradientStopCollection](../../gradientstopcollection), [LayoutSlideCollection](../../layoutslidecollection), Queue, [GlobalLayoutSlideCollection](../../globallayoutslidecollection), [TagCollection](../../tagcollection), [SequenceCollection](../../sequencecollection), [ControlCollection](../../controlcollection), [ExtraColorSchemeCollection](../../extracolorschemecollection), [SectionSlideCollection](../../sectionslidecollection), [ColorOperationCollection](../../coloroperationcollection), [VbaModuleCollection](../../vbamodulecollection), [CellCollection](../../cellcollection), KeyedCollection, [MathParagraph](../../mathparagraph), [VideoCollection](../../videocollection)


---


