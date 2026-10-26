---
title: DataLabel
second_title: Référence API Aspose.Slides pour C++
description: Représente les étiquettes d’une série.
type: docs
weight: 365
url: /fr/aspose.slides.charts/datalabel/
---
## DataLabel classe

Représente les étiquettes d’une série.

```cpp
class DataLabel : public Aspose::Slides::Charts::IDataLabel,
                  public Aspose::Slides::IDOMObject
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Initialise TextFrameForOverriding avec le texte du paramètre \"text\". Si TextFrameForOverriding est déjà initialisé, il modifie simplement son texte. |
|  [DataLabel](./datalabel/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) | Crée une nouvelle instance de la classe [DataLabel](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Spécifie la hauteur réelle de l’élément du graphique. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) avant pour obtenir les valeurs réelles. Lire **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Spécifie la largeur réelle de l’élément du graphique. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) avant pour obtenir les valeurs réelles. Lire **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Spécifie la position x réelle (gauche) de l’élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) avant pour obtenir les valeurs réelles. Lire **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Spécifie le haut réel de l’élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) avant pour obtenir les valeurs réelles. Lire **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Bas. Lecture seule **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Renvoie le graphique parent. Lecture seule [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() override | Renvoie le format de l’étiquette de données. Lecture seule [IDataLabelFormat](../idatalabelformat/). |
| **float** [get_Height](./get_height/)() override | Renvoie la hauteur d’un titre en tant que fraction de la hauteur du graphique. Lire **float**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | False signifie que l’étiquette de données n’est pas visible (et ainsi tous les indicateurs Show* (ShowValue, …) sont faux). Lecture seule **bool**. |
| **float** [get_Right](./get_right/)() override | Droite. Lecture seule **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Renvoie le format du texte. Lecture seule [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Peut contenir un texte richement formaté. Si cette propriété n’est pas nulle alors cette valeur de texte formaté remplace le texte généré automatiquement de l’étiquette de données. Le texte généré automatiquement de l’étiquette de données signifie le texte géré par les propriétés ShowSeriesName, ShowValue, … et formaté avec la propriété TextFormatManager.TextFormat. Lecture seule [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() override | Obtient la cellule de données du classeur. Appliqué si la propriété IDataLabelFormat::get(set)_ShowLabelValueFromCell est vraie. |
| **float** [get_Width](./get_width/)() override | Renvoie la largeur d’un titre en tant que fraction de la largeur du graphique. Lire **float**. |
| **float** [get_X](./get_x/)() override | Renvoie la coordonnée x d’un titre en tant que fraction de la largeur du graphique. Lire **float**. |
| **float** [get_Y](./get_y/)() override | Renvoie la coordonnée y d’un titre en tant que fraction de la hauteur du graphique. Lire **float**. |
| [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() override | Renvoie le texte réel de l’étiquette basé sur les paramètres [DataLabelFormat](../datalabelformat/) ou la valeur [get_TextFrameForOverriding()](./get_textframeforoverriding/)->get(set)_Text(). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Active le hachage des objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Hide](./hide/)() override | Rend l’étiquette de données cachée en réglant tous les indicateurs Show* (ShowValue, …) sur false. IsVisible sera false après cela. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Active le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées par la valeur spécifiée. |
| void [set_Height](./set_height/)(**float**) override | Définit la hauteur d’un titre en tant que fraction de la hauteur du graphique. Écrit **float**. |
| void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | Définit la cellule de données du classeur. Appliqué si la propriété IDataLabelFormat::get(set)_ShowLabelValueFromCell est vraie. |
| void [set_Width](./set_width/)(**float**) override | Définit la largeur d’un titre en tant que fraction de la largeur du graphique. Écrit **float**. |
| void [set_X](./set_x/)(**float**) override | Définit la coordonnée x d’un titre en tant que fraction de la largeur du graphique. Écrit **float**. |
| void [set_Y](./set_y/)(**float**) override | Définit la coordonnée y d’un titre en tant que fraction de la hauteur du graphique. Écrit **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Active la conversion d’objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [IDataLabel](../idatalabel/)
* Classe [IDOMObject](../../aspose.slides/idomobject/)
* Espace de noms [Aspose::Slides::Charts](../)
* Bibliothèque [Aspose.Slides](../../)