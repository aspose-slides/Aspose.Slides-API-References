---
title: Legend
second_title: Référence API Aspose.Slides pour C++
description: Représente les propriétés de la légende du graphique.
type: docs
weight: 1262
url: /fr/aspose.slides.charts/legend/
---
## Legend classe


Représente les propriétés de la légende du graphique.

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, un NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, un NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Spécifie la hauteur réelle de l’élément du graphique. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) avant pour obtenir les valeurs réelles. Lecture **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Spécifie la largeur réelle de l’élément du graphique. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) avant pour obtenir les valeurs réelles. Lecture **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Spécifie la position x réelle (gauche) de l’élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) avant pour obtenir les valeurs réelles. Lecture **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Spécifie le haut réel de l’élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) avant pour obtenir les valeurs réelles. Lecture **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Bas. Lecture seule **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Renvoie le graphique. Lecture seule [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | Obtient les entrées de la légende. Lecture seule [ILegendEntryCollection](../ilegendentrycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | Obtient les propriétés de l’entrée de légende correspondant au point de données du graphique à l’indice spécifié. Dans le cas des types de graphiques : bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, le point de données est pris à partir de la première série. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Renvoie le format d’une légende. Lecture seule [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Renvoie la hauteur d’une légende en fraction de la hauteur du graphique. Lecture **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Détermine si d’autres éléments du graphique peuvent chevaucher la légende. Lecture **bool**. |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | Spécifie la position de la légende sur un graphique. Les valeurs non NaN des propriétés X, Y, Width, Heigt remplacent l’effet de cette propriété. Lecture [LegendPositionType](../legendpositiontype/). |
| **float** [get_Right](./get_right/)() override | Droite. Lecture seule **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Format du texte. Lecture seule [IChartTextFormat](../icharttextformat/). |
| **float** [get_Width](./get_width/)() override | Renvoie la largeur d’une légende en fraction de la largeur du graphique. Lecture **float**. |
| **float** [get_X](./get_x/)() override | Renvoie la coordonnée x d’une légende en fraction de la largeur du graphique. Lecture **float**. |
| **float** [get_Y](./get_y/)() override | Renvoie la coordonnée y d’une légende en fraction de la hauteur du graphique. Lecture **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogique de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d’objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogique de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogique de l’opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogique de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [set_Height](./set_height/)(**float**) override | Définit la hauteur d’une légende en fraction de la hauteur du graphique. Écriture **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Détermine si d’autres éléments du graphique peuvent chevaucher la légende. Écriture **bool**. |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | Spécifie la position de la légende sur un graphique. Les valeurs non NaN des propriétés X, Y, Width, Heigt remplacent l’effet de cette propriété. Écriture [LegendPositionType](../legendpositiontype/). |
| void [set_Width](./set_width/)(**float**) override | Définit la largeur d’une légende en fraction de la largeur du graphique. Écriture **float**. |
| void [set_X](./set_x/)(**float**) override | Définit la coordonnée x d’une légende en fraction de la largeur du graphique. Écriture **float**. |
| void [set_Y](./set_y/)(**float**) override | Définit la coordonnée y d’une légende en fraction de la hauteur du graphique. Écriture **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogique de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |
## Voir aussi

* Classe [DomObject](../../aspose.slides/domobject/)
* Classe [ILegend](../ilegend/)
* Espace de noms [Aspose::Slides::Charts](../)
* Bibliothèque [Aspose.Slides](../../)