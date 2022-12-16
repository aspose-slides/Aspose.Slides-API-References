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
[CommentCollection](../../commentcollection), [BehaviorPropertyCollection](../../behaviorpropertycollection), [LineFormatCollection](../../lineformatcollection), [ColumnCollection](../../columncollection), SortedList, [ChartDataWorksheetCollection](../../chartdataworksheetcollection), [EffectStyleCollection](../../effectstylecollection), [GradientStopCollectionEffectiveData](../../gradientstopcollectioneffectivedata), [SmartArtNodeCollection](../../smartartnodecollection), [DigitalSignatureCollection](../../digitalsignaturecollection), [TabCollection](../../tabcollection), [PieSplitCustomPointCollection](../../piesplitcustompointcollection), [SlideCollection](../../slidecollection), List, [ChartCategoryCollection](../../chartcategorycollection), [SmartArtShapeCollection](../../smartartshapecollection), [ShapeCollection](../../shapecollection), [ImageTransformOperationCollection](../../imagetransformoperationcollection), [FontFallBackRulesCollection](../../fontfallbackrulescollection), SortedDictionary, [Sequence](../../sequence), [RowCollection](../../rowcollection), [SummaryZoomSectionCollection](../../summaryzoomsectioncollection), LinkedList, [ChartSeriesCollection](../../chartseriescollection), Stack, [ChartCellCollection](../../chartcellcollection), [CommentAuthorCollection](../../commentauthorcollection), Collection, [AudioCollection](../../audiocollection), [Row](../../row), [DataLabelCollection](../../datalabelcollection), [CustomXmlPartCollection](../../customxmlpartcollection), Dictionary, [MathBlock](../../mathblock), [ImageTransformOCollectionEffectiveData](../../imagetransformocollectioneffectivedata), [TrendlineCollection](../../trendlinecollection), [ParagraphCollection](../../paragraphcollection), [MasterSlideCollection](../../masterslidecollection), [TextAnimationCollection](../../textanimationcollection), ReadOnlyCollection, [SectionCollection](../../sectioncollection), [MotionPath](../../motionpath), [ChartDataPointCollection](../../chartdatapointcollection), [ControlPropertiesCollection](../../controlpropertiescollection), [FontSubstRuleCollection](../../fontsubstrulecollection), [BehaviorCollection](../../behaviorcollection), [VbaReferenceCollection](../../vbareferencecollection), [Column](../../column), [PointCollection](../../pointcollection), [ImageCollection](../../imagecollection), [FillFormatCollection](../../fillformatcollection), [MasterLayoutSlideCollection](../../masterlayoutslidecollection), [GradientStopCollection](../../gradientstopcollection), [PortionCollection](../../portioncollection), Queue, [LayoutSlideCollection](../../layoutslidecollection), [GlobalLayoutSlideCollection](../../globallayoutslidecollection), [TagCollection](../../tagcollection), [SequenceCollection](../../sequencecollection), [ControlCollection](../../controlcollection), [ExtraColorSchemeCollection](../../extracolorschemecollection), [SectionSlideCollection](../../sectionslidecollection), [ColorOperationCollection](../../coloroperationcollection), [VbaModuleCollection](../../vbamodulecollection), [CellCollection](../../cellcollection), KeyedCollection, [MathParagraph](../../mathparagraph), [VideoCollection](../../videocollection)


---


