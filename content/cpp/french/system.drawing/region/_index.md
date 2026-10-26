---
title: Region
second_title: Référence API Aspose.Slides pour C++
description: "Représente l'intérieur d'une forme graphique. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject() . Ne jamais créer d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Toujours encapsuler cette classe dans un pointeur System::SmartPtr et utiliser ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 261
url: /fr/system.drawing/region/
---
## Classe Region

Représente l'intérieur d'une forme graphique. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions comme argument.

```cpp
class Region : public System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | Renvoie une copie de l'objet actuel. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | Remplace la région représentée par l'objet actuel par la partie de la région définie par le rectangle spécifié qui n'intersecte pas cette région. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | Remplace la région représentée par l'objet actuel par la partie de la région définie par le rectangle spécifié qui n'intersecte pas cette région. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Remplace la région représentée par l'objet actuel par la partie de la région définie par le chemin spécifié qui n'intersecte pas cette région. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Remplace la région représentée par l'objet actuel par la partie de la région spécifiée qui n'intersecte pas cette région. |
| void [Dispose](./dispose/)() | Libère toutes les ressources du système d'exploitation acquises par l'objet actuel. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Détermine si la région spécifiée est identique à la région représentée par l'objet actuel sur la surface de dessin spécifiée. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | Remplace la région représentée par l'objet actuel par le résultat de l'exclusion de la région définie par le rectangle spécifié. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | Remplace la région représentée par l'objet actuel par le résultat de l'exclusion de la région définie par le rectangle spécifié. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Remplace la région représentée par l'objet actuel par le résultat de l'exclusion de la région définie par le chemin spécifié. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Remplace la région représentée par l'objet actuel par le résultat de l'exclusion de la région spécifiée. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Obtient une structure [RectangleF](../rectanglef/) qui représente un rectangle englobant ce [Region](./) sur la surface de dessin d'un objet [Graphics](../graphics/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | Renvoie un objet RegionData contenant les données qui définissent la région représentée par l'objet actuel. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | Renvoie un tableau de structures [RectangleF](../rectanglef/) qui approximent ce [Region](./) après l'application de la transformation matricielle spécifiée. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | Remplace la région représentée par l'objet actuel par le résultat de l'intersection de cette région avec une région définie par le rectangle spécifié. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | Remplace la région représentée par l'objet actuel par le résultat de l'intersection de cette région avec une région définie par le rectangle spécifié. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Remplace la région représentée par l'objet actuel par le résultat de l'intersection de cette région avec une région définie par le chemin spécifié. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Remplace la région représentée par l'objet actuel par le résultat de l'intersection de cette région avec la région spécifiée. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Détermine si la région représentée par l'objet actuel possède un intérieur vide sur la surface de dessin spécifiée. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Détermine si la région représentée par l'objet actuel possède un intérieur infini sur la surface de dessin spécifiée. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | Détermine si le point spécifié est contenu dans la région représentée par l'objet actuel. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | Détermine si le point spécifié est contenu dans la région représentée par l'objet actuel. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | Détermine si une partie du rectangle spécifié est contenue dans la région représentée par l'objet actuel. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | Détermine si une partie du rectangle spécifié est contenue dans la région représentée par l'objet actuel. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Détermine si le point spécifié est contenu dans la région représentée par l'objet actuel en utilisant les graphiques spécifiés. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Détermine si le point spécifié est contenu dans la région représentée par l'objet actuel en utilisant les graphiques spécifiés. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Détermine si une partie du rectangle spécifié est contenue dans la région représentée par l'objet actuel en utilisant les graphiques spécifiés. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Détermine si une partie du rectangle spécifié est contenue dans la région représentée par l'objet actuel en utilisant les graphiques spécifiés. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | Détermine si le point spécifié est contenu dans la région représentée par l'objet actuel. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Détermine si le point spécifié est contenu dans la région représentée par l'objet actuel en utilisant les graphiques spécifiés. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| void [MakeEmpty](./makeempty/)() | Initialise l'objet actuel avec un intérieur vide. |
| void [MakeInfinite](./makeinfinite/)() | Initialise cet objet région avec un intérieur infini. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, vraiment, il initialise simplement un nouvel objet et permet la copie de construction des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, vraiment, il initialise simplement un nouvel objet et permet la copie de construction des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
|  [Region](./region/)() | Construit une nouvelle instance de la classe [Region](./). |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | Construit une nouvelle instance de la classe [Region](./) qui représente une région définie par le rectangle spécifié. |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | Construit une nouvelle instance de la classe [Region](./) qui représente une région définie par le rectangle spécifié. |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Construit une nouvelle instance de la classe [Region](./) qui représente une région définie par le chemin spécifié. |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | Construit une nouvelle instance de la classe [Region](./) qui représente une région définie par l'objet RegionData spécifié. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Transforme cette région par la matrice spécifiée. |
| void [Transform](./transform/)(const SkMatrix\&) | Transforme cette région par la matrice spécifiée. |
| void [Translate](./translate/)(int, int) | Déplace les coordonnées de la région du montant spécifié. |
| void [Translate](./translate/)(**float**, **float**) | Déplace les coordonnées de la région du montant spécifié. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | Remplace la région représentée par l'objet actuel par le résultat de l'opération d'union de cette région avec une région définie par le rectangle spécifié. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | Remplace la région représentée par l'objet actuel par le résultat de l'union de cette région avec une région définie par le rectangle spécifié. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Remplace la région représentée par l'objet actuel par le résultat de l'union de cette région avec une région définie par le chemin spécifié. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Remplace la région représentée par l'objet actuel par le résultat de l'union de cette région avec la région spécifiée. |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | Remplace la région représentée par l'objet actuel par les parties de cette région et de la région définie par le rectangle spécifié qui n'intersectent pas. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | Remplace la région représentée par l'objet actuel par les parties de cette région et de la région définie par le rectangle spécifié qui n'intersectent pas. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Remplace la région représentée par l'objet actuel par les parties de cette région et de la région définie par le chemin spécifié qui n'intersectent pas. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Remplace la région représentée par l'objet actuel par les parties de cette région et de la région spécifiée qui n'intersectent pas. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |
| virtual  [~Region](./~region/)() | Destructeur. |

## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [System::Drawing](../)
* Bibliothèque [Aspose.Slides](../../)