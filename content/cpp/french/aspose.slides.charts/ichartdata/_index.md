---
title: IChartData
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente les données utilisées pour le tracé d'un graphique.
type: docs
weight: 651
url: /fr/aspose.slides.charts/ichartdata/
---
## IChartData classe

Représente les données utilisées pour le tracé d’un graphique.

```cpp
class IChartData : public virtual System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() | Obtient les catégories principales (ou les catégories principales et secondaires si [IChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) est défini sur false). Lecture seule [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) | Renvoie la catégorie principale à l’indice spécifié. Si [get_UseSecondaryCategories](./get_usesecondarycategories/) est false, récupère parmi toutes les catégories. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() | Obtient la fabrique de cellules pour créer les cellules utilisées pour les séries ou les catégories du graphique. Lecture seule [IChartDataWorkbook](../ichartdataworkbook/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Renvoie la série à l’indice spécifié. |
| virtual [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() | Représente la source de données du graphique |
| virtual [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() | Obtient le type du classeur incorporé. Renvoie [WorkbookType::NotDefined](../workbooktype/) si [IChartData::get_DataSourceType](./get_datasourcetype/) est [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/). Lecture seule [WorkbookType](../workbooktype/). |
| virtual [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() | Représente le chemin du classeur externe si la source de données est externe, null sinon |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() | Obtient les catégories secondaires si [IChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) est true. Lecture seule [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) | Renvoie la catégorie secondaire à l’indice spécifié. Si [get_UseSecondaryCategories](./get_usesecondarycategories/) est false, alors [IChartData::get_SecondaryCategories](./get_secondarycategories/) est null. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() | Obtient les séries. Lecture seule [IChartSeriesCollection](../ichartseriescollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) | Renvoie le groupe de séries à l’indice spécifié. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() | Obtient les groupes de séries. Lecture seule [IChartSeriesGroupCollection](../ichartseriesgroupcollection/). |
| virtual **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() | Si défini sur false, alors [IChartData::get_SecondaryCategories](./get_secondarycategories/) renvoie null et les données dans [IChartData::get_Categories](./get_categories/) sont utilisées à la fois pour les séries principales et secondaires. Si défini sur true, alors les données dans [IChartData::get_SecondaryCategories](./get_secondarycategories/) sont utilisées pour les séries secondaires et les données dans [IChartData::get_Categories](./get_categories/) sont utilisées pour les séries principales. Lire **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de référence associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d’objets personnalisés. |
| virtual [System::String](../../system/string/) [GetRange](./getrange/)() | Obtient la plage de données du graphique. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, vraiment, il initialise simplement un nouvel objet et permet de copier la construction des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, vraiment, il initialise simplement un nouvel objet et permet de copier la construction des sous-classes. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() | Écrit le classeur [Excel](../../aspose.slides.excel/) contenue en interne dans un flux en mémoire. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de référence partagé du nombre spécifié. |
| virtual void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) | Si défini sur false, alors [IChartData::get_SecondaryCategories](./get_secondarycategories/) renvoie null et les données dans [IChartData::get_Categories](./get_categories/) sont utilisées à la fois pour les séries principales et secondaires. Si défini sur true, alors les données dans [IChartData::get_SecondaryCategories](./get_secondarycategories/) sont utilisées pour les séries secondaires et les données dans [IChartData::get_Categories](./get_categories/) sont utilisées pour les séries principales. Écrire **bool**. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) | Définit le classeur externe comme source de données pour le graphique. Les données [Chart](../chart/) seront mises à jour à partir du classeur cible. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) | Définit le classeur externe comme source de données pour le graphique. |
| virtual void [SetRange](./setrange/)([System::String](../../system/string/)) | Définit la plage de données du graphique. Les séries et les catégories seront mises à jour en fonction de la nouvelle plage de données. Si le nombre de séries dans la plage de données est supérieur au nombre de séries dans les données du graphique, alors des séries supplémentaires du même type que la dernière série de la collection actuelle seront ajoutées à la fin de la collection. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de référence partagé. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de référence partagé. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de référence partagé. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual void [SwitchRowColumn](./switchrowcolumn/)() | Échange les données entre les axes. Les données tracées sur l’axe X seront déplacées vers l’axe Y et inversement. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct typeof([System.Object](../../system/object/)) de C#. |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de référence faible. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de référence faible. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) | Initialise le classeur [Excel](../../aspose.slides.excel/) contenue en interne avec la valeur spécifiée par l’utilisateur. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |
## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [Aspose::Slides::Charts](../)
* Bibliothèque [Aspose.Slides](../../)