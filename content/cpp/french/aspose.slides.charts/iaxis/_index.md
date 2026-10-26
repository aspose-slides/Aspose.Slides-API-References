---
title: IAxis
second_title: Référence de l'API Aspose.Slides pour C++
description: Encapsule l'objet qui représente l'axe d'un graphique.
type: docs
weight: 534
url: /fr/aspose.slides.charts/iaxis/
---
## IAxis classe

Encapsule l'objet qui représente l'axe d'un graphique.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | Spécifie l'unité principale réelle de l'axe. Appelez d'abord la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pour obtenir la valeur réelle. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | Spécifie l'échelle réelle de l'unité principale de l'axe. Appelez d'abord la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pour obtenir la valeur réelle. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | Spécifie la valeur maximale réelle sur l'axe. Appelez d'abord la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pour obtenir la valeur réelle. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | Spécifie l'unité mineure réelle de l'axe. Appelez d'abord la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pour obtenir la valeur réelle. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | Spécifie l'échelle réelle de l'unité mineure de l'axe. Appelez d'abord la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pour obtenir la valeur réelle. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | Spécifie la valeur minimale réelle sur l'axe. Appelez d'abord la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pour obtenir la valeur réelle. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | Représente le type d'agrégation de l'axe de catégorie (regroupement). Appliqué à la catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | Indique si l'axe de valeur croise l'axe de catégorie entre les catégories. Cette propriété ne s'applique qu'aux axes de catégorie et ne s'applique pas aux graphiques 3D. Lecture **bool**. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | Spécifie la plus petite unité de temps représentée sur l'axe de date. Lecture [TimeUnitType](../timeunittype/). |
| virtual **double** [get_BinWidth](./get_binwidth/)() | Spécifie la largeur du groupe lorsque la propriété AggregationType est définie sur [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | Spécifie le type de l'axe de catégorie. Lecture [CategoryAxisType](../categoryaxistype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Renvoie le graphique. Lecture seule [IChart](../ichart/). |
| virtual **float** [get_CrossAt](./get_crossat/)() | Représente le point sur l'axe où l'axe perpendiculaire le croise. Lecture **float**. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | Représente le CrossType sur l'axe spécifié où l'autre axe le croise. Lecture [CrossesType](../crossestype/). |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | Spécifie la valeur d'échelle des unités d'affichage pour l'axe de valeur. Lecture [DisplayUnitType](../displayunittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | Représente le format de l'axe. Lecture seule [IAxisFormat](../iaxisformat/). |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Détermine si un axe possède un titre visible. Lecture **bool**. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | Indique si l'unité principale de l'axe est attribuée automatiquement. Lecture **bool**. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | Indique si la valeur maximale est attribuée automatiquement. Lecture **bool**. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | Indique si l'unité mineure de l'axe est attribuée automatiquement. Lecture **bool**. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | Indique si la valeur minimale est attribuée automatiquement. Lecture **bool**. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | Spécifie la valeur du groupe de dépassement automatique. Si false : utilisez la propriété OverflowBin. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | Spécifie la valeur d'espacement automatique des étiquettes de repères. Si false : utilisez la propriété TickLabelSpacing. Lecture **bool**. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | Spécifie la valeur d'espacement automatique des marques de repères. Si false : utilisez la propriété TickMarksSpacing. Lecture **bool**. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | Spécifie la valeur du groupe de sous-dépassement automatique. Si false : utilisez la propriété UnderflowBin. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | Indique si le type d'échelle de l'axe de valeur est logarithmique ou non. Lecture **bool**. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Indique si le format est lié aux données sources. Lecture **bool**. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | Indique si le groupe de dépassement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du groupe de dépassement. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | Indique si MS PowerPoint trace les points de données du dernier au premier. Lecture **bool**. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | Indique si le groupe de sous-dépassement est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du groupe de sous-dépassement. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Indique si l'axe est visible. Lecture **bool**. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | Spécifie la distance des étiquettes par rapport à l'axe. Appliqué aux axes de catégorie ou de date. La valeur doit être comprise entre 0 % et 1000 %. Lecture **uint16_t**. |
| virtual **double** [get_LogBase](./get_logbase/)() | Représente la base logarithmique. La valeur par défaut est 10. Lecture **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | Représente le format des lignes de grille majeures sur un axe de graphique. Lecture seule [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | Représente le type de repère majeur pour l'axe spécifié. Lecture [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | Représente les unités majeures pour l'axe de date ou de valeur. Lecture **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | Représente l'échelle de l'unité majeure pour l'axe de date. Lecture [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | Représente la valeur maximale sur l'axe de valeur. Lecture **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | Représente le format des lignes de grille mineures sur un axe de graphique. Lecture seule [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | Représente le type de repère mineur pour l'axe spécifié. Lecture [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | Représente les unités mineures pour l'axe de date ou de valeur. Lecture **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | Représente l'échelle de l'unité majeure pour l'axe de date. Lecture [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MinValue](./get_minvalue/)() | Représente la valeur minimale sur l'axe de valeur. Lecture **double**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Représente la chaîne de format pour les étiquettes [Axis](../axis/). Lecture [System::String](../../system/string/). |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | Spécifie le nombre de groupes lorsque la propriété AggregationType est définie sur [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | Spécifie la valeur personnalisée du groupe de dépassement. Appliqué lorsque la propriété IsAutomaticOverflowBin est définie sur false et que la propriété IsOverflowBin est vraie. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | Représente la position de l'axe. Lecture [AxisPositionType](../axispositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Renvoie la présentation. Lecture seule [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | Indique si les lignes de grille majeures sont affichées. Lecture seule **bool**. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | Indique si les lignes de grille mineures sont affichées. Lecture seule **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Renvoie la diapositive de base. Lecture seule [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Renvoie le format du texte du graphique. Lecture seule [IChartTextFormat](../icharttextformat/). |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | Représente la position des étiquettes de repères sur l'axe spécifié. Lecture [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | Représente l'angle de rotation des étiquettes de repère. Lecture **float**. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | Spécifie le nombre d'étiquettes de repère à sauter entre les étiquettes dessinées. Lecture **uint32_t**. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | Spécifie le nombre de marques de repère à sauter avant que la suivante ne soit dessinée. Appliqué aux axes de catégorie ou de série. Lecture **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | Obtient le titre de l'axe. Lecture seule [IChartTitle](../icharttitle/). |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | Spécifie la valeur personnalisée du groupe de sous-dépassement. Appliqué lorsque la propriété IsAutomaticUnderflowBin est définie sur false et que la propriété IsUnderflowBin est vraie. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|   [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien en réalité, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien en réalité, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | Représente le type d'agrégation de l'axe de catégorie (regroupement). Appliqué à la catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | Indique si l'axe de valeur croise l'axe de catégorie entre les catégories. Cette propriété ne s'applique qu'aux axes de catégorie et ne s'applique pas aux graphiques 3D. Écriture **bool**. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | Spécifie la plus petite unité de temps représentée sur l'axe de date. Écriture [TimeUnitType](../timeunittype/). |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | Spécifie la largeur du groupe lorsque la propriété AggregationType est définie sur [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | Spécifie le type de l'axe de catégorie. Écriture [CategoryAxisType](../categoryaxistype/). |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | Représente le point sur l'axe où l'axe perpendiculaire le croise. Écriture **float**. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | Représente le CrossType sur l'axe spécifié où l'autre axe le croise. Écriture [CrossesType](../crossestype/). |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | Spécifie la valeur d'échelle des unités d'affichage pour l'axe de valeur. Écriture [DisplayUnitType](../displayunittype/). |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Détermine si un axe possède un titre visible. Écriture **bool**. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | Indique si l'unité principale de l'axe est attribuée automatiquement. Écriture **bool**. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | Indique si la valeur maximale est attribuée automatiquement. Écriture **bool**. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | Indique si l'unité mineure de l'axe est attribuée automatiquement. Écriture **bool**. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | Indique si la valeur minimale est attribuée automatiquement. Écriture **bool**. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | Spécifie la valeur du groupe de dépassement automatique. Si false : utilisez la propriété OverflowBin. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | Spécifie la valeur d'espacement automatique des étiquettes de repères. Si false : utilisez la propriété TickLabelSpacing. Écriture **bool**. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | Spécifie la valeur d'espacement automatique des marques de repères. Si false : utilisez la propriété TickMarksSpacing. Écriture **bool**. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | Spécifie la valeur du groupe de sous-dépassement automatique. Si false : utilisez la propriété UnderflowBin. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | Indique si le type d'échelle de l'axe de valeur est logarithmique ou non. Écriture **bool**. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Indique si le format est lié aux données sources. Écriture **bool**. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | Indique si le groupe de dépassement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du groupe de dépassement. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | Indique si MS PowerPoint trace les points de données du dernier au premier. Écriture **bool**. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | Indique si le groupe de sous-dépassement est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du groupe de sous-dépassement. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | Indique si l'axe est visible. Écriture **bool**. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | Spécifie la distance des étiquettes par rapport à l'axe. Appliqué aux axes de catégorie ou de date. La valeur doit être comprise entre 0 % et 1000 %. Écriture **uint16_t**. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | Représente la base logarithmique. La valeur par défaut est 10. Écriture **double**. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | Représente le type de repère majeur pour l'axe spécifié. Écriture [TickMarkType](../tickmarktype/). |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | Représente les unités majeures pour l'axe de date ou de valeur. Écriture **double**. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | Représente l'échelle de l'unité majeure pour l'axe de date. Écriture [TimeUnitType](../timeunittype/). |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | Représente la valeur maximale sur l'axe de valeur. Écriture **double**. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | Représente le type de repère mineur pour l'axe spécifié. Écriture [TickMarkType](../tickmarktype/). |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | Représente les unités mineures pour l'axe de date ou de valeur. Écriture **double**. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | Représente l'échelle de l'unité majeure pour l'axe de date. Écriture [TimeUnitType](../timeunittype/). |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | Représente la valeur minimale sur l'axe de valeur. Écriture **double**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Représente la chaîne de format pour les étiquettes [Axis](../axis/). Écriture [System::String](../../system/string/). |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | Spécifie le nombre de groupes lorsque la propriété AggregationType est définie sur [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | Spécifie la valeur personnalisée du groupe de dépassement. Appliqué lorsque la propriété IsAutomaticOverflowBin est définie sur false et que la propriété IsOverflowBin est vraie. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | Représente la position de l'axe. Écriture [AxisPositionType](../axispositiontype/). |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | Représente la position des étiquettes de repère sur l'axe spécifié. Écriture [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | Représente l'angle de rotation des étiquettes de repère. Écriture **float**. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | Spécifie le nombre d'étiquettes de repère à sauter entre les étiquettes dessinées. Écriture **uint32_t**. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | Spécifie le nombre de marques de repère à sauter avant que la suivante ne soit dessinée. Appliqué aux axes de catégorie ou de série. Écriture **uint16_t**. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | Spécifie la valeur personnalisée du groupe de sous-dépassement. Appliqué lorsque la propriété IsAutomaticUnderflowBin est définie sur false et que la propriété IsUnderflowBin est vraie. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | Définit la propriété IAxis::get(set)_CategoryAxisType avec une valeur déterminée automatiquement à partir des données de l'axe. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [IFormattedTextContainer](../iformattedtextcontainer/)
* Espace de noms [Aspose::Slides::Charts](../)
* Bibliothèque [Aspose.Slides](../../)