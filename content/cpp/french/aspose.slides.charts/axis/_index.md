---
title: Axis
second_title: Référence API Aspose.Slides pour C++
description: Encapsule l'objet qui représente l'axe d'un graphique.
type: docs
weight: 14
url: /fr/aspose.slides.charts/axis/
---
## Axis classe

Encapsule l'objet qui représente l'axe d'un graphique.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | Spécifie l'unité majeure réelle de l'axe. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) précédemment pour obtenir la valeur réelle. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | Spécifie l'échelle de l'unité majeure réelle de l'axe. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) précédemment pour obtenir la valeur réelle. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | Spécifie la valeur maximale réelle sur l'axe. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) précédemment pour obtenir la valeur réelle. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | Spécifie l'unité mineure réelle de l'axe. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) précédemment pour obtenir la valeur réelle. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | Spécifie l'échelle de l'unité mineure réelle de l'axe. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) précédemment pour obtenir la valeur réelle. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | Spécifie la valeur minimale réelle sur l'axe. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) précédemment pour obtenir la valeur réelle. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | Représente le type d'agrégation de l'axe de catégorie (regroupement). Appliqué aux catégories. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | Représente si l'axe des valeurs croise l'axe des catégories entre les catégories. Cette propriété s'applique uniquement aux axes de catégorie et ne s'applique pas aux graphiques 3D. Lecture **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | Spécifie la plus petite unité de temps représentée sur l'axe des dates. Lecture [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | Spécifie la largeur du bin lorsque la valeur de la propriété AggregationType est définie à [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | Spécifie le type de l'axe de catégorie. Lecture [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Renvoie le graphique parent. Lecture seule [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | Représente le point sur l'axe où l'axe perpendiculaire le croise. Lecture **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | Représente le CrossType sur l'axe spécifié où l'autre axe le croise. Lecture [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | Spécifie la valeur d'échelle des unités d'affichage pour l'axe des valeurs. Lecture [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | Représente le format de l'axe. Lecture seule [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | Détermine si un axe possède un titre visible. Lecture **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | Indique si l'unité majeure de l'axe est assignée automatiquement. Lecture **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | Indique si la valeur maximale est assignée automatiquement. Lecture **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | Indique si l'unité mineure de l'axe est assignée automatiquement. Lecture **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | Indique si la valeur minimale est assignée automatiquement. Lecture **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | Spécifie la valeur automatique du bin de dépassement. Si false : utilisez la propriété OverflowBin. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | Spécifie la valeur automatique de l'espacement des libellés de graduation. Si false : utilisez la propriété TickLabelSpacing. Lecture **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | Spécifie la valeur automatique de l'espacement des marques de graduation. Si false : utilisez la propriété TickMarksSpacing. Lecture **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | Spécifie la valeur automatique du bin de sous-flux. Si false : utilisez la propriété UnderflowBin. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | Représente si le type d'échelle de l'axe des valeurs est logarithmique ou non. Lecture **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Indique si le format est lié aux données source. Lecture **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | Spécifie si le bin de dépassement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bin de dépassement. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | Représente si MS PowerPoint trace les points de données du dernier au premier. Lecture **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | Spécifie si le bin de sous-flux est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bin de sous-flux. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Représente si l'axe est visible. Lecture **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | Spécifie la distance des libellés par rapport à l'axe. Appliqué aux axes de catégorie ou de date. La valeur doit être comprise entre 0 % et 1000 %. Lecture **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | Représente la base logarithmique. La valeur par défaut est 10. Lecture **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | Représente le format des principales lignes de grille sur un axe de graphique. Lecture seule [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | Représente le type de graduation principale pour l'axe spécifié. Lecture [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | Représente les unités majeures pour l'axe de date ou de valeur. Lecture **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | Représente l'échelle de l'unité majeure pour l'axe de date. Lecture [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | Représente la valeur maximale sur l'axe des valeurs. Lecture **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | Représente le format des lignes de grille mineures sur un axe de graphique. Lecture seule [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | Représente le type de graduation mineure pour l'axe spécifié. Lecture [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | Représente les unités mineures pour l'axe de date ou de valeur. Lecture **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | Représente l'échelle de l'unité majeure pour l'axe de date. Lecture [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | Représente la valeur minimale sur l'axe des valeurs. Lecture **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Représente la chaîne de format pour les libellés [Axis](./). Lecture [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | Spécifie le nombre de bins lorsque la valeur de la propriété AggregationType est définie à [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | Spécifie la valeur personnalisée du bin de dépassement. Appliqué lorsque la propriété IsAutomaticOverflowBin est définie sur false et que la propriété IsOverflowBin est vraie. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | Représente la position de l'axe. Lecture [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | Pour masquer la ligne de grille principale, définissez [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() à [FillType::NoFill](../../aspose.slides/filltype/). Lecture seule **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | Pour masquer la ligne de grille mineure, définissez [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() à [FillType::NoFill](../../aspose.slides/filltype/). Lecture seule **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Représente le format du texte. Lecture seule [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | Représente la position des libellés des graduations sur l'axe spécifié. Lecture [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | Représente l'angle de rotation des libellés de graduation. Lecture **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | Spécifie combien de libellés de graduation sauter entre les libellés dessinés. Appliqué aux axes de catégorie ou de série. Lecture **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | Spécifie combien de marques de graduation doivent être sautées avant que la suivante ne soit dessinée. Appliqué aux axes de catégorie ou de série. Lecture **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | Obtient le titre de l'axe. Lecture seule [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | Spécifie la valeur personnalisée du bin de sous-flux. Appliqué lorsque la propriété IsAutomaticUnderflowBin est définie sur false et que la propriété IsUnderflowBin est vraie. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet de cloner des types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet de copier les sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'assignation. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet de copier les sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées d'une valeur spécifiée. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | Représente le type d'agrégation de l'axe de catégorie (regroupement). Appliqué aux catégories. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | Représente si l'axe des valeurs croise l'axe des catégories entre les catégories. Cette propriété s'applique uniquement aux axes de catégorie et ne s'applique pas aux graphiques 3D. Écriture **bool**. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | Spécifie la plus petite unité de temps représentée sur l'axe des dates. Écriture [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | Spécifie la largeur du bin lorsque la valeur de la propriété AggregationType est définie à [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | Spécifie le type de l'axe de catégorie. Écriture [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | Représente le point sur l'axe où l'axe perpendiculaire le croise. Écriture **float**. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | Représente le CrossType sur l'axe spécifié où l'autre axe le croise. Écriture [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | Spécifie la valeur d'échelle des unités d'affichage pour l'axe des valeurs. Écriture [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Détermine si un axe possède un titre visible. Écriture **bool**. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | Indique si l'unité majeure de l'axe est assignée automatiquement. Écriture **bool**. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | Indique si la valeur maximale est assignée automatiquement. Écriture **bool**. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | Indique si l'unité mineure de l'axe est assignée automatiquement. Écriture **bool**. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | Indique si la valeur minimale est assignée automatiquement. Écriture **bool**. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | Spécifie la valeur automatique du bin de dépassement. Si false : utilisez la propriété OverflowBin. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | Spécifie la valeur automatique de l'espacement des libellés de graduation. Si false : utilisez la propriété TickLabelSpacing. Écriture **bool**. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | Spécifie la valeur automatique de l'espacement des marques de graduation. Si false : utilisez la propriété TickMarksSpacing. Écriture **bool**. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | Spécifie la valeur automatique du bin de sous-flux. Si false : utilisez la propriété UnderflowBin. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | Représente si le type d'échelle de l'axe des valeurs est logarithmique ou non. Écriture **bool**. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Indique si le format est lié aux données source. Écriture **bool**. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | Spécifie si le bin de dépassement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bin de dépassement. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | Représente si MS PowerPoint trace les points de données du dernier au premier. Écriture **bool**. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | Spécifie si le bin de sous-flux est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bin de sous-flux. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Représente si l'axe est visible. Écriture **bool**. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | Spécifie la distance des libellés par rapport à l'axe. Appliqué aux axes de catégorie ou de date. La valeur doit être comprise entre 0 % et 1000 %. Écriture **uint16_t**. |
| void [set_LogBase](./set_logbase/)(**double**) override | Représente la base logarithmique. La valeur par défaut est 10. Écriture **double**. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | Représente le type de graduation principale pour l'axe spécifié. Écriture [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | Représente les unités majeures pour l'axe de date ou de valeur. Écriture **double**. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | Représente l'échelle de l'unité majeure pour l'axe de date. Écriture [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | Représente la valeur maximale sur l'axe des valeurs. Écriture **double**. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | Représente le type de graduation mineure pour l'axe spécifié. Écriture [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | Représente les unités mineures pour l'axe de date ou de valeur. Écriture **double**. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | Représente l'échelle de l'unité majeure pour l'axe de date. Écriture [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | Représente la valeur minimale sur l'axe des valeurs. Écriture **double**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Représente la chaîne de format pour les libellés [Axis](./). Écriture [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | Spécifie le nombre de bins lorsque la valeur de la propriété AggregationType est définie à [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | Spécifie la valeur personnalisée du bin de dépassement. Appliqué lorsque la propriété IsAutomaticOverflowBin est définie sur false et que la propriété IsOverflowBin est vraie. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | Représente la position de l'axe. Écriture [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | Représente la position des libellés des graduations sur l'axe spécifié. Écriture [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | Représente l'angle de rotation des libellés de graduation. Écriture **float**. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | Spécifie combien de libellés de graduation sauter entre les libellés dessinés. Appliqué aux axes de catégorie ou de série. Écriture **uint32_t**. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | Spécifie combien de marques de graduation doivent être sautées avant que la suivante ne soit dessinée. Appliqué aux axes de catégorie ou de série. Écriture **uint16_t**. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | Spécifie la valeur personnalisée du bin de sous-flux. Appliqué lorsque la propriété IsAutomaticUnderflowBin est définie sur false et que la propriété IsUnderflowBin est vraie. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | Définit la propriété IAxis::get(set)_CategoryAxisType avec une valeur déterminée automatiquement en fonction des données de l'axe. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Définit le n-ième argument de modèle comme pointeur faible (au lieu de partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct typeof([System.Object](../../system/object/)) de C#. |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [DomObject](../../aspose.slides/domobject/)
* Classe [IAxis](../iaxis/)
* Espace de noms [Aspose::Slides::Charts](../)
* Bibliothèque [Aspose.Slides](../../)