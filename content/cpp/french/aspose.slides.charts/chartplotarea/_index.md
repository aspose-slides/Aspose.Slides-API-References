---
title: ChartPlotArea
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le rectangle où le graphique doit être tracé.
type: docs
weight: 248
url: /fr/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea classe


Représente le rectangle où le graphique doit être tracé.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant les sémantiques C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Spécifie la hauteur réelle de l’élément du graphique. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) avant pour obtenir les valeurs réelles. Lecture **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Spécifie la largeur réelle de l’élément du graphique. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) avant pour obtenir les valeurs réelles. Lecture **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Spécifie la position x réelle (gauche) de l’élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) avant pour obtenir les valeurs réelles. Lecture **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Spécifie le haut réel de l’élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) avant pour obtenir les valeurs réelles. Lecture **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Bas. Lecture seule **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). Lecture seule [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Retourne le format d’une zone de tracé. Lecture seule [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Retourne la hauteur d’une boîte englobante de zone de tracé en tant que fraction de la hauteur du graphique (de 0 à 1). Lecture **float**. |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | Définit comment la position doit être calculée : true \\u2013 calculé automatiquement ; défini par les propriétés X, Y, Width, Height. Lecture seule **bool**. |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | Si la disposition de la zone de tracé est définie manuellement, cette propriété indique si la zone de tracé doit être disposée par l’intérieur (sans inclure les axes et les libellés d’axes) ou par l’extérieur (en incluant les axes et les libellés d’axes). Lecture [LayoutTargetType](../layouttargettype/). |
| **float** [get_Right](./get_right/)() override | Droite. Lecture seule **float**. |
| **float** [get_Width](./get_width/)() override | Retourne la largeur d’une boîte englobante de zone de tracé en tant que fraction de la largeur du graphique (de 0 à 1). Lecture **float**. |
| **float** [get_X](./get_x/)() override | Retourne la coordonnée x du coin supérieur gauche de la boîte englobante de zone de tracé en tant que fraction de la largeur du graphique (de 0 à 1). Lecture **float**. |
| **float** [get_Y](./get_y/)() override | Retourne la coordonnée y du coin supérieur gauche de la boîte englobante de zone de tracé en tant que fraction de la hauteur du graphique (de 0 à 1). Lecture **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d’objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Met en œuvre le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement le nouvel objet et permet la construction copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, en réalité, il initialise simplement le nouvel objet et permet la construction copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [set_Height](./set_height/)(**float**) override | Définit la hauteur d’une boîte englobante de zone de tracé en tant que fraction de la hauteur du graphique (de 0 à 1). Écriture **float**. |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | Si la disposition de la zone de tracé est définie manuellement, cette propriété indique si la zone de tracé doit être disposée par l’intérieur (sans inclure les axes et les libellés d’axes) ou par l’extérieur (en incluant les axes et les libellés d’axes). Écriture [LayoutTargetType](../layouttargettype/). |
| void [set_Width](./set_width/)(**float**) override | Définit la largeur d’une boîte englobante de zone de tracé en tant que fraction de la largeur du graphique (de 0 à 1). Écriture **float**. |
| void [set_X](./set_x/)(**float**) override | Définit la coordonnée x du coin supérieur gauche de la boîte englobante de zone de tracé en tant que fraction de la largeur du graphique (de 0 à 1). Écriture **float**. |
| void [set_Y](./set_y/)(**float**) override | Définit la coordonnée y du coin supérieur gauche de la boîte englobante de zone de tracé en tant que fraction de la hauteur du graphique (de 0 à 1). Écriture **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Met en œuvre la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Met en œuvre le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [DomObject](../../aspose.slides/domobject/)
* Classe [IChartPlotArea](../ichartplotarea/)
* Espace de noms [Aspose::Slides::Charts](../)
* Bibliothèque [Aspose.Slides](../../)