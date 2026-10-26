---
title: IChartSeriesGroup
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente un groupe de séries.
type: docs
weight: 846
url: /fr/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup classe

Représente un groupe de séries.

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux bien que selon IEC 60559:1989 le NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux bien que selon IEC 60559:1989 le NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | Spécifie comment les valeurs de taille de bulle sont représentées sur le diagramme à bulles. Lecture [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | Spécifie le facteur d'échelle pour le diagramme à bulles (peut être entre 0 et 300 % de la taille par défaut). Lecture **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Renvoie le diagramme. Lecture seule [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Renvoie la série du diagramme dans le groupe à l'index spécifié. |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | Spécifie la taille du trou dans un diagramme en beignet (peut être entre 10 et 90 % de la taille de la zone graphique). Lecture **uint8_t**. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | Obtient l'angle de la première tranche du diagramme en secteurs ou en beignet, en degrés (dans le sens des aiguilles d'une montre à partir du haut, de 0 à 360 degrés). Lecture **uint16_t**. |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | Renvoie la distance, exprimée en pourcentage de la largeur du marqueur, entre les séries de données dans un diagramme 3D. Lecture **uint16_t**. |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | Spécifie l'espacement entre les grappes de barres ou de colonnes, exprimé en pourcentage de la largeur de la barre ou de la colonne. Lecture **uint16_t**. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | Vrai si le diagramme possède des lignes de séries. Appliqué aux diagrammes à barres empilées et OfPie. Lecture **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | Spécifie le format HiLowLines. HiLowLines appliqué avec les types de diagrammes HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | Spécifie que chaque marqueur de données dans la série a une couleur différente. Lecture **bool**. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | Spécifie le chevauchement des barres et colonnes sur les diagrammes 2D, exprimé en pourcentage (de -100 % à 100 %). |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | Spécifie comment déterminer quels points de données sont dans le deuxième secteur ou la deuxième barre d'un diagramme en secteurs emboîtés ou en barres emboîtées. Lecture [PieSplitType](../piesplittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | Les informations de séparation personnalisées pour un diagramme en secteurs emboîtés ou en barres emboîtées avec une séparation personnalisée. Renvoie le point de données qui doit être dessiné dans le deuxième secteur ou la deuxième barre d'un tel diagramme selon l'index. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | Les informations de séparation personnalisées pour un diagramme en secteurs emboîtés ou en barres emboîtées avec une séparation personnalisée. Contient les points de données qui doivent être dessinés dans le deuxième secteur ou la deuxième barre d'un tel diagramme. Lecture seule [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données sont dans le deuxième secteur ou la deuxième barre d'un diagramme en secteurs emboîtés ou en barres emboîtées. Utilisée avec la propriété PieSplitBy. Lecture **double**. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | Indique si les séries de ce groupe sont tracées sur un axe secondaire. Lecture seule **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Renvoie la présentation. Lecture seule [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | Spécifie la taille du deuxième secteur ou de la deuxième barre d'un diagramme en secteurs emboîtés ou en barres emboîtées, exprimée en pourcentage de la taille du premier secteur (peut être entre 5 et 200 %). Lecture **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | Renvoie une collection en lecture seule de séries de diagramme. Lecture seule [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Renvoie la diapositive de base. Lecture seule [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | Renvoie le type de ce groupe de séries. Lecture seule [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | Fournit l'accès aux barres haut/bas d'un diagramme en ligne ou en cours. Lecture seule [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | Obtient l'élément à l'index spécifié. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Met en œuvre le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, vraiment, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, vraiment, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | Spécifie comment les valeurs de taille de bulle sont représentées sur le diagramme à bulles. Écriture [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | Spécifie le facteur d'échelle pour le diagramme à bulles (peut être entre 0 et 300 % de la taille par défaut). Écriture **int32_t**. |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | Spécifie la taille du trou dans un diagramme en beignet (peut être entre 10 et 90 % de la taille de la zone graphique). Écriture **uint8_t**. |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | Définit l'angle de la première tranche du diagramme en secteurs ou en beignet, en degrés (dans le sens des aiguilles d'une montre à partir du haut, de 0 à 360 degrés). Écriture **uint16_t**. |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | Définit la distance, exprimée en pourcentage de la largeur du marqueur, entre les séries de données dans un diagramme 3D. Écriture **uint16_t**. |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | Spécifie l'espacement entre les grappes de barres ou de colonnes, exprimé en pourcentage de la largeur de la barre ou de la colonne. Écriture **uint16_t**. |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | Vrai si le diagramme possède des lignes de séries. Appliqué aux diagrammes à barres empilées et OfPie. Écriture **bool**. |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | Spécifie que chaque marqueur de données dans la série a une couleur différente. Écriture **bool**. |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | Spécifie le chevauchement des barres et colonnes sur les diagrammes 2D, exprimé en pourcentage (de -100 % à 100 %). |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | Spécifie comment déterminer quels points de données sont dans le deuxième secteur ou la deuxième barre d'un diagramme en secteurs emboîtés ou en barres emboîtées. Écriture [PieSplitType](../piesplittype/). |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données sont dans le deuxième secteur ou la deuxième barre d'un diagramme en secteurs emboîtés ou en barres emboîtées. Utilisée avec la propriété PieSplitBy. Écriture **double**. |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | Spécifie la taille du deuxième secteur ou de la deuxième barre d'un diagramme en secteurs emboîtés ou en barres emboîtées, exprimée en pourcentage de la taille du premier secteur (peut être entre 5 et 200 %). Écriture **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Met en œuvre la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Met en œuvre le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Remarques

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup. 2) Le groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (« propriétés de groupe de séries »). Les « propriétés de groupe de séries » dans la classe [ChartSeriesGroup](../chartseriesgroup/) sont lecture/écriture. Chacune des « propriétés de groupe de séries » peut avoir une projection lecture seule dans la classe [ChartSeries](../chartseries/).

## Voir aussi

* Classe [IChartComponent](../ichartcomponent/)
* Espace de noms [Aspose::Slides::Charts](../)
* Bibliothèque [Aspose.Slides](../../)