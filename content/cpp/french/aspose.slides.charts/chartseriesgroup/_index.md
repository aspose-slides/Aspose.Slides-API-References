---
title: ChartSeriesGroup
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente un groupe de séries.
type: docs
weight: 300
url: /fr/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup classe

Représente un groupe de séries.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## Méthodes

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. Lire [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | Spécifie le facteur d’échelle pour le graphique à bulles (peut être entre 0 et 300 % de la taille par défaut). Lire **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Renvoie le graphique parent. Lecture seule [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | Renvoie la série de graphique du groupe à l’indice spécifié. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | Spécifie la taille du trou dans un graphique en anneau (peut être entre 0 et 90 % de la taille de la zone de tracé). Lire **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | Obtient l’angle de la première tranche de camembert ou d’anneau, en degrés (dans le sens horaire à partir du haut, de 0 à 360 degrés). Lire **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | Renvoie la distance, exprimée en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Lire **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | Spécifie l’espace entre les regroupements de barres ou de colonnes, exprimé en pourcentage de la largeur de la barre ou de la colonne. Lire **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | Vrai si le graphique possède des lignes de série. Appliqué aux graphiques à barres empilées et OfPie. Lire **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | Spécifie le format HiLowLines. HiLowLines s’applique aux types de graphiques HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | Spécifie que chaque marqueur de données de la série a une couleur différente. Lire **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | Spécifie de combien les barres et colonnes doivent se chevaucher sur les graphiques 2-D, exprimé en pourcentage (de -100 % à 100 %). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | Spécifie comment déterminer quels points de données se trouvent dans le deuxième camembert ou barre d’un graphique pie-of-pie ou bar-of-pie. Lire [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | Les informations de division personnalisées pour un graphique pie-of-pie ou bar-of-pie avec une division personnalisée. Renvoie le point de données qui doit être dessiné dans le deuxième camembert ou barre d’un graphique pie-of-pie ou bar-of-pie par index. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | Les informations de division personnalisées pour un graphique pie-of-pie ou bar-of-pie avec une division personnalisée. Contient les points de données qui doivent être dessinés dans le deuxième camembert ou barre d’un graphique pie-of-pie ou bar-of-pie. Lecture seule [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans le deuxième camembert ou barre d’un graphique pie-of-pie ou bar-of-pie. Utilisée conjointement avec la propriété PieSplitBy. Lire **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | Indique si les séries de ce groupe sont tracées sur un axe secondaire. Lecture seule **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | Spécifie la taille du deuxième camembert ou barre d’un graphique pie-of-pie ou bar-of-pie, exprimée en pourcentage de la taille du premier camembert (peut être entre 5 et 200 %). Lire **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | Renvoie une collection de séries. Lecture seule [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | Renvoie le type de ce groupe de séries. Lecture seule [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | Fournit l’accès aux barres haut/bas d’un graphique en ligne ou en actions. Lecture seule [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d’objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | Obtient l’élément à l’indice spécifié. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la construction de copies des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la construction de copies des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l’objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles. Écrire [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | Spécifie le facteur d’échelle pour le graphique à bulles (peut être entre 0 et 300 %). Écrire **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | Spécifie la taille du trou dans un graphique en anneau (peut être entre 0 et 90 %). Écrire **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | Définit l’angle de la première tranche de camembert ou d’anneau, en degrés (dans le sens horaire à partir du haut, de 0 à 360 degrés). Écrire **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | Définit la distance, exprimée en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D. Écrire **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | Spécifie l’espace entre les regroupements de barres ou de colonnes, exprimé en pourcentage de la largeur de la barre ou de la colonne. Écrire **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | Vrai si le graphique possède des lignes de série. Appliqué aux graphiques à barres empilées et OfPie. Écrire **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | Spécifie que chaque marqueur de données de la série a une couleur différente. Écrire **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | Spécifie de combien les barres et colonnes doivent se chevaucher sur les graphiques 2-D, exprimé en pourcentage (de -100 % à 100 %). |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | Spécifie comment déterminer quels points de données se trouvent dans le deuxième camembert ou barre d’un graphique pie-of-pie ou bar-of-pie. Écrire [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans le deuxième camembert ou barre d’un graphique pie-of-pie ou bar-of-pie. Utilisée conjointement avec la propriété PieSplitBy. Écrire **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | Spécifie la taille du deuxième camembert ou barre d’un graphique pie-of-pie ou bar-of-pie, exprimée en pourcentage de la taille du premier camembert (peut être entre 5 et 200 %). Écrire **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Remarques

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l’énumération CombinableSeriesTypesGroup. 2) Le groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (« propriétés du groupe de séries »). Les « propriétés du groupe de séries » dans la classe [ChartSeriesGroup](./) sont lecture/écriture. Chaque « propriété du groupe de séries » peut avoir une projection en lecture seule dans la classe [ChartSeries](../chartseries/).

## Voir aussi

* Classe [IChartSeriesGroup](../ichartseriesgroup/)
* Classe [IDOMObject](../../aspose.slides/idomobject/)
* Espace de noms [Aspose::Slides::Charts](../)
* Bibliothèque [Aspose.Slides](../../)