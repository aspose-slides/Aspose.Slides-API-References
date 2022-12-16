---
title: shapes
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/collect/shapes/
---

## shapes([Presentation](../../presentation) pres)  method

 Collects all instances of  Shape in the  Presentation. 
 

 
```php
  $pres = new Presentation("pres.pptx");
  try {
    for ($shape : Collect->shapes($pres)) {
      // if the shape is AutoShape, add a black solid border
      if ($shape instanceof AutoShape) {
        $autoShape = $shape;
        $autoShape->getLineFormat()->setStyle(LineStyle.Single);
        $autoShape->getLineFormat()->setWidth(10.0);
        $autoShape->getLineFormat()->getFillFormat()->setFillType(FillType.Solid);
        $autoShape->getLineFormat()->getFillFormat()->getSolidFillColor()->setColor(Color::black);
      }
    }
    $pres->save("pres-out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../presentation) | Presentation to collect shapes |

### Returns
[CommentCollection](../../commentcollection), [BehaviorPropertyCollection](../../behaviorpropertycollection), [LineFormatCollection](../../lineformatcollection), [ColumnCollection](../../columncollection), SortedList, [ChartDataWorksheetCollection](../../chartdataworksheetcollection), [EffectStyleCollection](../../effectstylecollection), [GradientStopCollectionEffectiveData](../../gradientstopcollectioneffectivedata), [SmartArtNodeCollection](../../smartartnodecollection), [DigitalSignatureCollection](../../digitalsignaturecollection), [TabCollection](../../tabcollection), [PieSplitCustomPointCollection](../../piesplitcustompointcollection), [SlideCollection](../../slidecollection), List, [ChartCategoryCollection](../../chartcategorycollection), [SmartArtShapeCollection](../../smartartshapecollection), [ShapeCollection](../../shapecollection), [ImageTransformOperationCollection](../../imagetransformoperationcollection), [FontFallBackRulesCollection](../../fontfallbackrulescollection), SortedDictionary, [Sequence](../../sequence), [RowCollection](../../rowcollection), [SummaryZoomSectionCollection](../../summaryzoomsectioncollection), LinkedList, [ChartSeriesCollection](../../chartseriescollection), Stack, [ChartCellCollection](../../chartcellcollection), [CommentAuthorCollection](../../commentauthorcollection), Collection, [AudioCollection](../../audiocollection), [Row](../../row), [DataLabelCollection](../../datalabelcollection), [CustomXmlPartCollection](../../customxmlpartcollection), Dictionary, [MathBlock](../../mathblock), [ImageTransformOCollectionEffectiveData](../../imagetransformocollectioneffectivedata), [TrendlineCollection](../../trendlinecollection), [ParagraphCollection](../../paragraphcollection), [MasterSlideCollection](../../masterslidecollection), [TextAnimationCollection](../../textanimationcollection), ReadOnlyCollection, [SectionCollection](../../sectioncollection), [MotionPath](../../motionpath), [ChartDataPointCollection](../../chartdatapointcollection), [ControlPropertiesCollection](../../controlpropertiescollection), [FontSubstRuleCollection](../../fontsubstrulecollection), [BehaviorCollection](../../behaviorcollection), [VbaReferenceCollection](../../vbareferencecollection), [Column](../../column), [PointCollection](../../pointcollection), [ImageCollection](../../imagecollection), [FillFormatCollection](../../fillformatcollection), [MasterLayoutSlideCollection](../../masterlayoutslidecollection), [GradientStopCollection](../../gradientstopcollection), [PortionCollection](../../portioncollection), Queue, [LayoutSlideCollection](../../layoutslidecollection), [GlobalLayoutSlideCollection](../../globallayoutslidecollection), [TagCollection](../../tagcollection), [SequenceCollection](../../sequencecollection), [ControlCollection](../../controlcollection), [ExtraColorSchemeCollection](../../extracolorschemecollection), [SectionSlideCollection](../../sectionslidecollection), [ColorOperationCollection](../../coloroperationcollection), [VbaModuleCollection](../../vbamodulecollection), [CellCollection](../../cellcollection), KeyedCollection, [MathParagraph](../../mathparagraph), [VideoCollection](../../videocollection)


---


