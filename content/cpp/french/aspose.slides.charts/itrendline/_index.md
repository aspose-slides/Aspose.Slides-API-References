---
title: ITrendline
second_title: Référence de l'API Aspose.Slides pour C++
description: Classe représentant la ligne de tendance d'une série de diagramme
type: docs
weight: 1223
url: /fr/aspose.slides.charts/itrendline/
---
## ITrendline classe

La classe représente la ligne de tendance d’une série de diagramme

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Initialise TextFrameForOverriding avec le texte du paramètre \"text\". Si TextFrameForOverriding est déjà initialisé, il modifie simplement son texte. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres flottants de type C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual **double** [get_Backward](./get_backward/)() | Spécifie le nombre de catégories (ou d’unités sur un diagramme de dispersion) que la ligne de tendance s’étend avant les données de la série en cours de tendance. Sur les diagrammes de dispersion et non-dispersion, la valeur doit être toute valeur non négative. Lecture **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Renvoie le diagramme. Lecture seule [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | Spécifie que l’équation de la ligne de tendance est affichée sur le diagramme (dans la même étiquette que la valeur Rsquared). Lecture **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | Spécifie que la valeur R-carré de la ligne de tendance est affichée sur le diagramme (dans la même étiquette que l’équation). Lecture **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Représente le format de la ligne de tendance. Lecture [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | Spécifie le nombre de catégories (ou d’unités sur un diagramme de dispersion) que la ligne de tendance s’étend après les données de la série en cours de tendance. Sur les diagrammes de dispersion et non-dispersion, la valeur doit être toute valeur non négative. Lecture **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | Spécifie la valeur où la ligne de tendance doit croiser l’axe des y. Cette propriété n’est prise en charge que lorsque le type de ligne de tendance est exp, linéaire ou polynomial. Lecture **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | Spécifie l’ordre de la ligne de tendance polynomiale. Elle est ignorée pour les autres types de lignes de tendance. La valeur doit être comprise entre 2 et 6. Lecture **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | Spécifie la période de la ligne de tendance pour une ligne de tendance moyenne mobile. Elle est ignorée pour les autres variantes de ligne de tendance. La valeur doit être comprise entre 2 et 255. Lecture **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Renvoie la présentation. Lecture seule [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Représente l’entrée de légende liée à cette ligne de tendance. Lecture seule [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Renvoie la diapositive de base. Lecture seule [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Renvoie le format de texte du diagramme. Lecture seule [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Peut contenir un texte riche formaté. Si cette propriété n’est pas nulle, alors cette valeur de texte formaté remplace le texte généré automatiquement. Le texte généré automatiquement est une propriété implicite de l’étiquette de données, de l’étiquette d’unité d’affichage de l’axe des valeurs, du titre de l’axe, du titre du diagramme, de l’étiquette de la ligne de tendance. Le texte généré automatiquement est formaté avec la propriété [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Lecture seule [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | Obtient le nom de la ligne de tendance. Lecture [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | Obtient le type de ligne de tendance. Lecture [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d’objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Met en œuvre le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, vraiment, il se contente d’initialiser un nouvel objet et permet de construire des sous-classes par copie. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, vraiment, il se contente d’initialiser un nouvel objet et permet de construire des sous-classes par copie. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l’objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [set_Backward](./set_backward/)(**double**) | Spécifie le nombre de catégories (ou d’unités sur un diagramme de dispersion) que la ligne de tendance s’étend avant les données de la série en cours de tendance. Sur les diagrammes de dispersion et non-dispersion, la valeur doit être toute valeur non négative. Écriture **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | Spécifie que l’équation de la ligne de tendance est affichée sur le diagramme (dans la même étiquette que la valeur Rsquared). Écriture **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | Spécifie que la valeur R-carré de la ligne de tendance est affichée sur le diagramme (dans la même étiquette que l’équation). Écriture **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Représente le format de la ligne de tendance. Écriture [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | Spécifie le nombre de catégories (ou d’unités sur un diagramme de dispersion) que la ligne de tendance s’étend après les données de la série en cours de tendance. Sur les diagrammes de dispersion et non-dispersion, la valeur doit être toute valeur non négative. Écriture **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | Spécifie la valeur où la ligne de tendance doit croiser l’axe des y. Cette propriété n’est prise en charge que lorsque le type de ligne de tendance est exp, linéaire ou poly. Écriture **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | Spécifie l’ordre de la ligne de tendance polynomiale. Elle est ignorée pour les autres types de lignes de tendance. La valeur doit être comprise entre 2 et 6. Écriture **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | Spécifie la période de la ligne de tendance pour une ligne de tendance moyenne mobile. Elle est ignorée pour les autres variantes de ligne de tendance. La valeur doit être comprise entre 2 et 255. Écriture **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | Définit le nom de la ligne de tendance. Écriture [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | Définit le type de ligne de tendance. Écriture [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Met en œuvre la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Met en œuvre le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [IOverridableText](../ioverridabletext/)
* Espace de noms [Aspose::Slides::Charts](../)
* Bibliothèque [Aspose.Slides](../../)