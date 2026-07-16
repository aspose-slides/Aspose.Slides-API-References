---
title: GraphicsPath
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente un ensemble de lignes et de courbes connectées. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défauts d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument."
type: docs
weight: 66
url: /fr/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath classe


Représente un ensemble de lignes et de courbes connectées. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défauts d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument.

```cpp
class GraphicsPath : public System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | Ajoute l'arc elliptique spécifié au chemin représenté par l'objet actuel. |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | Ajoute l'arc elliptique spécifié au chemin représenté par l'objet actuel. |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | Ajoute l'arc elliptique spécifié au chemin représenté par l'objet actuel. |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Ajoute l'arc elliptique spécifié au chemin représenté par l'objet actuel. |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Ajoute la courbe cubique de Bézier spécifiée au chemin représenté par l'objet actuel. |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Ajoute la courbe cubique de Bézier spécifiée au chemin représenté par l'objet actuel. |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Ajoute la courbe cubique de Bézier spécifiée au chemin représenté par l'objet actuel. |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | Ajoute la courbe cubique de Bézier spécifiée au chemin représenté par l'objet actuel. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Ajoute une séquence de courbes cubiques de Bézier connectées à la figure actuelle. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Ajoute une séquence de courbes cubiques de Bézier connectées à la figure actuelle. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Ajoute la courbe fermée spécifiée au chemin représenté par l'objet actuel. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Ajoute la courbe fermée spécifiée au chemin représenté par l'objet actuel. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Ajoute la courbe spécifiée au chemin représenté par l'objet actuel. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Ajoute la courbe spécifiée au chemin représenté par l'objet actuel. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | Ajoute la courbe spécifiée au chemin représenté par l'objet actuel. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | Ajoute la courbe spécifiée au chemin représenté par l'objet actuel. |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | Ajoute l'ellipse spécifiée au chemin représenté par l'objet actuel. |
| void [AddEllipse](./addellipse/)(int, int, int, int) | Ajoute l'ellipse spécifiée au chemin représenté par l'objet actuel. |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Ajoute l'ellipse spécifiée au chemin représenté par l'objet actuel. |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Ajoute l'ellipse spécifiée au chemin représenté par l'objet actuel. |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Ajoute la ligne spécifiée au chemin représenté par l'objet actuel. |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Ajoute la ligne spécifiée au chemin représenté par l'objet actuel. |
| void [AddLine](./addline/)(int, int, int, int) | Ajoute la ligne spécifiée au chemin représenté par l'objet actuel. |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | Ajoute la ligne spécifiée au chemin représenté par l'objet actuel. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Ajoute la série de segments de ligne connectés spécifiée au chemin représenté par l'objet actuel. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Ajoute la série de segments de ligne connectés spécifiée au chemin représenté par l'objet actuel. |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | Ajoute le chemin spécifié au chemin représenté par l'objet actuel. |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | Ajoute le contour de forme de tarte spécifié au chemin représenté par l'objet actuel. |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | Ajoute le contour de forme de tarte spécifié au chemin représenté par l'objet actuel. |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Ajoute le contour de forme de tarte spécifié au chemin représenté par l'objet actuel. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Ajoute le polygone spécifié au chemin représenté par l'objet actuel. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Ajoute le polygone spécifié au chemin représenté par l'objet actuel. |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Ajoute le rectangle spécifié au chemin représenté par l'objet actuel. |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Ajoute le rectangle spécifié au chemin représenté par l'objet actuel. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | Ajoute la série de rectangles spécifiée au chemin représenté par l'objet actuel. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | Ajoute la série de rectangles spécifiée au chemin représenté par l'objet actuel. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Ajoute une chaîne de texte au chemin représenté par l'objet actuel. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Ajoute une chaîne de texte au chemin représenté par l'objet actuel. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Ajoute une chaîne de texte au chemin représenté par l'objet actuel. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Ajoute une chaîne de texte au chemin représenté par l'objet actuel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | Crée une copie de l'objet actuel. |
| void [CloseAllFigures](./closeallfigures/)() | Ferme toutes les figures ouvertes et en démarre une nouvelle. |
| void [CloseFigure](./closefigure/)() | Ferme la figure actuelle et en démarre une nouvelle. |
| void [Dispose](./dispose/)() | Libère toutes les ressources du système d'exploitation acquises par l'objet actuel. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de type C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de type C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| void [Flatten](./flatten/)() | Aplati chaque courbe du chemin en les convertissant en une série de lignes connectées. La valeur de platitude de 0.25 est utilisée. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | Aplati chaque courbe du chemin en les convertissant en une série de lignes connectées. La valeur de platitude de 0.25 est utilisée. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | Aplati chaque courbe du chemin en les convertissant en une série de lignes connectées. |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | Renvoie le mode de remplissage de l'objet actuel. |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | Retourne un objet [PathData](../pathdata/) contenant les points qui composent un chemin représenté par l'objet actuel et leurs types. |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | Retourne un tableau contenant les points qui composent un chemin représenté par l'objet actuel. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | Retourne un tableau contenant les valeurs qui indiquent les types des points qui composent un chemin représenté par l'objet actuel. |
| int [get_PointCount](./get_pointcount/)() const | Retourne le nombre de points du chemin représenté par l'objet actuel. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | Retourne un objet [RectangleF](../../system.drawing/rectanglef/) qui représente un rectangle englobant le chemin représenté par l'objet actuel lorsqu'il est transformé avec la matrice spécifiée. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de référence associée à l'objet. |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | Retourne une valeur qui est une combinaison binaire des valeurs Detail::FigureType indiquant quels types de figures sont contenus dans le chemin représenté par l'objet actuel. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | Retourne un objet [PointF](../../system.drawing/pointf/) représentant le dernier point du chemin. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | Construit une nouvelle instance de la classe [GraphicsPath](./) avec le mode de remplissage spécifié. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Construit une nouvelle instance de l'objet [GraphicsPath](./) qui représente le chemin spécifié. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Construit une nouvelle instance de l'objet [GraphicsPath](./) qui représente le chemin spécifié. |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Indique si le point spécifié est contenu dans le contour de ce [GraphicsPath](./) lorsqu'il est dessiné avec le [Pen](../../system.drawing/pen/) spécifié. NON IMPLEMENTÉ. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | Détermine si le point spécifié est contenu dans le chemin représenté par l'objet actuel. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | Détermine si le point spécifié est contenu dans le chemin représenté par l'objet actuel. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [Reset](./reset/)() | Vide le chemin en enlevant tous les points. |
| void [Reverse](./reverse/)() | Inverse l'ordre des points dans le tableau PathPoints de ce [GraphicsPath](./). |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | Définit le mode de remplissage de l'objet actuel. |
| void [SetMarkers](./setmarkers/)() | NON IMPLEMENTÉ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [StartFigure](./startfigure/)() | Démarre une nouvelle figure. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | Transforme le chemin représenté par l'objet actuel en appliquant la matrice de transformation spécifiée. |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Remplace ce chemin par un contour autour du chemin original. |
|  [~GraphicsPath](./~graphicspath/)() | Destructeur. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.Slides](../../)