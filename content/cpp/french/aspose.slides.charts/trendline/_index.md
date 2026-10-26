---
title: Trendline
second_title: Référence de l'API Aspose.Slides pour C++
description: Classe représente la ligne de tendance d’une série de graphique
type: docs
weight: 1366
url: /fr/aspose.slides.charts/trendline/
---
## Classe Trendline

La classe représente la ligne de tendance d’une série de graphique

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Initialise TextFrameForOverriding avec le texte du paramètre \"text\". Si TextFrameForOverriding est déjà initialisé, il modifie simplement son texte. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si selon IEC 60559:1989 NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si selon IEC 60559:1989 NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| **double** [get_Backward](./get_backward/)() override | Spécifie le nombre de catégories (ou unités sur un graphique de dispersion) que la ligne de tendance s'étend avant les données de la série qui est tendance. Sur les graphiques de dispersion et non-dispersion, la valeur doit être toute valeur non négative. Lire **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Renvoie le graphique parent. Lecture seule [IChart](../ichart/). |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | Spécifie que l'équation de la ligne de tendance est affichée sur le graphique (dans la même étiquette que Rsquaredvalue). Lire **bool**. |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | Spécifie que la valeur R-carré de la ligne de tendance est affichée sur le graphique (dans la même étiquette que l'équation). Lire **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Représente le format de la ligne de tendance. Lire [IFormat](../iformat/). |
| **double** [get_Forward](./get_forward/)() override | Spécifie le nombre de catégories (ou unités sur un graphique de dispersion) que la ligne de tendance s'étend après les données de la série qui est tendance. Sur les graphiques de dispersion et non-dispersion, la valeur doit être toute valeur non négative. Lire **double**. |
| **double** [get_Intercept](./get_intercept/)() override | Spécifie la valeur où la ligne de tendance doit traverser l'axe y. Cette propriété n'est prise en charge que lorsque le type de ligne de tendance est exp, linear ou poly. Lire **double**. |
| **uint8_t** [get_Order](./get_order/)() override | Spécifie l'ordre de la ligne de tendance polynomiale. Elle est ignorée pour les autres types de lignes de tendance. La valeur doit être comprise entre 2 et 6. Lire **uint8_t**. |
| **uint8_t** [get_Period](./get_period/)() override | Spécifie la période de la ligne de tendance pour une ligne de tendance moyenne mobile. Elle est ignorée pour les autres variantes de ligne de tendance. La valeur doit être comprise entre 2 et 255. Lire **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | Représente l'entrée de légende liée à cette ligne de tendance Lecture seule [ILegendEntryProperties](../ilegendentryproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Renvoie le format du texte. Lecture seule [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Peut contenir un texte riche formaté. Si cette propriété n'est pas nulle, alors cette valeur de texte formaté remplace le texte auto-généré de l'étiquette de données. Le texte auto-généré de l'étiquette de données désigne le texte géré par les propriétés ShowSeriesName, ShowValue, … et formaté avec la propriété TextFormatManager.TextFormat. Lecture seule [ITextFrame](../../aspose.slides/itextframe/). |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | Obtient le nom de la ligne de tendance. Lire [System::String](../../system/string/). |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | Obtient le type de la ligne de tendance. Lire [Charts::TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, vraiment, il initialise simplement le nouvel objet et permet la construction de copies des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, vraiment, il initialise simplement le nouvel objet et permet la construction de copies des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [set_Backward](./set_backward/)(**double**) override | Spécifie le nombre de catégories (ou unités sur un graphique de dispersion) que la ligne de tendance s'étend avant les données de la série qui est tendance. Sur les graphiques de dispersion et non-dispersion, la valeur doit être toute valeur non négative. Écrire **double**. |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | Spécifie que l'équation de la ligne de tendance est affichée sur le graphique (dans la même étiquette que Rsquaredvalue). Écrire **bool**. |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | Spécifie que la valeur R-carré de la ligne de tendance est affichée sur le graphique (dans la même étiquette que l'équation). Écrire **bool**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Représente le format de la ligne de tendance. Écrire [IFormat](../iformat/). |
| void [set_Forward](./set_forward/)(**double**) override | Spécifie le nombre de catégories (ou unités sur un graphique de dispersion) que la ligne de tendance s'étend après les données de la série qui est tendance. Sur les graphiques de dispersion et non-dispersion, la valeur doit être toute valeur non négative. Écrire **double**. |
| void [set_Intercept](./set_intercept/)(**double**) override | Spécifie la valeur où la ligne de tendance doit traverser l'axe y. Cette propriété n'est prise en charge que lorsque le type de ligne de tendance est exp, linear ou poly. Écrire **double**. |
| void [set_Order](./set_order/)(**uint8_t**) override | Spécifie l'ordre de la ligne de tendance polynomiale. Elle est ignorée pour les autres types de lignes de tendance. La valeur doit être comprise entre 2 et 6. Écrire **uint8_t**. |
| void [set_Period](./set_period/)(**uint8_t**) override | Spécifie la période de la ligne de tendance pour une ligne de tendance moyenne mobile. Elle est ignorée pour les autres variantes de ligne de tendance. La valeur doit être comprise entre 2 et 255. Écrire **uint8_t**. |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | Définit le nom de la ligne de tendance. Écrire [System::String](../../system/string/). |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | Définit le type de la ligne de tendance. Écrire [Charts::TrendlineType](../trendlinetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
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
* Classe [ITrendline](../itrendline/)
* Espace de noms [Aspose::Slides::Charts](../)
* Bibliothèque [Aspose.Slides](../../)