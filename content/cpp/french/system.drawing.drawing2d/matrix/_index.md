---
title: Matrix
second_title: Référence API Aspose.Slides pour C++
description: "Représente une matrice 3x3 qui définit les opérations de transformation. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 118
url: /fr/system.drawing.drawing2d/matrix/
---
## Matrix classe


Représente une matrice 3x3 qui définit les opérations de transformation. Les objets de cette classe doivent être alloués uniquement à l’aide de la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d’instance de ce type sur la pile ou en utilisant l’opérateur new, car cela entraînera des erreurs d’exécution et/ou des fautes d’assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu’argument.

```cpp
class Matrix : public System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | Crée une copie de l'objet actuel. |
| void [Dispose](./dispose/)() | Libère toutes les ressources du système d'exploitation acquises par l'objet actuel. |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | Teste si l'objet spécifié est un [Matrix](./) et est identique à cet objet. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | Renvoie un tableau contenant les éléments de la matrice dans l'ordre suivant : m11, m12, m21, m22, dx, dy. |
| **bool** [get_IsIdentity](./get_isidentity/)() const | Détermine si la matrice représentée par l'objet actuel est une matrice identité. |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | Détermine si la matrice représentée par l'objet actuel est inversible. |
| **float** [get_OffsetX](./get_offsetx/)() const | Renvoie la valeur de translation X de la matrice représentée par l'objet actuel. |
| **float** [get_OffsetY](./get_offsety/)() const | Renvoie la valeur de translation Y de la matrice représentée par l'objet actuel. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Invert](./invert/)() | Inverse la matrice représentée par l'objet actuel. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
|  [Matrix](./matrix/)() | Construit une nouvelle instance de la classe [Matrix](./) qui représente une matrice identité. |
|  [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | Construit une nouvelle instance de la classe [Matrix](./) et l'initialise avec les valeurs spécifiées. |
|  [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Construit une nouvelle instance de la classe [Matrix](./) pour la transformation géométrique définie par le rectangle spécifié et le tableau de points. |
|  [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Construit une nouvelle instance de la classe [Matrix](./) pour la transformation géométrique définie par le rectangle spécifié et le tableau de points. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | Multiplie la matrice représentée par l'objet actuel par la matrice spécifiée. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | Multiplie la matrice représentée par l'objet actuel par la matrice spécifiée. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, se contente d'initialiser un nouvel objet et permet la construction de copies des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'assignation. Ne copie rien, en réalité, se contente d'initialiser un nouvel objet et permet la construction de copies des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du montant spécifié. |
| void [Reset](./reset/)() | Réinitialise la matrice représentée par l'objet actuel afin qu'elle devienne une matrice identité. |
| void [Rotate](./rotate/)(**float**) | Fait pivoter la matrice représentée par l'objet actuel dans le sens horaire de l'angle spécifié. |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | Fait pivoter la matrice représentée par l'objet actuel dans le sens horaire autour de l'origine de l'angle spécifié. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | Fait pivoter la matrice représentée par l'objet actuel dans le sens horaire autour du point spécifié de l'angle spécifié. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | Fait pivoter la matrice représentée par l'objet actuel dans le sens horaire autour du point spécifié de l'angle spécifié. |
| void [Scale](./scale/)(**float**, **float**) | Applique le vecteur d'échelle spécifié à la matrice représentée par l'objet actuel. |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Applique le vecteur d'échelle spécifié à la matrice représentée par l'objet actuel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [Shear](./shear/)(**float**, **float**) | Applique le vecteur de cisaillement spécifié à la matrice représentée par l'objet actuel. |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Applique le vecteur de cisaillement spécifié à la matrice représentée par l'objet actuel. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Applique la transformation géométrique définie par la matrice représentée par l'objet actuel aux points spécifiés. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Applique la transformation géométrique définie par la matrice représentée par l'objet actuel aux points spécifiés. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Applique la transformation géométrique définie par la matrice représentée par l'objet actuel aux points spécifiés. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Applique la transformation géométrique définie par la matrice représentée par l'objet actuel aux points spécifiés. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Applique uniquement les composantes d'échelle et de rotation de la matrice représentée par l'objet actuel aux points spécifiés. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Applique uniquement les composantes d'échelle et de rotation de la matrice représentée par l'objet actuel aux points spécifiés. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Applique uniquement les composantes d'échelle et de rotation de la matrice représentée par l'objet actuel aux points spécifiés. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Applique uniquement les composantes d'échelle et de rotation de la matrice représentée par l'objet actuel aux points spécifiés. |
| void [Translate](./translate/)(**float**, **float**) | Applique le vecteur de translation spécifié à la matrice représentée par l'objet actuel. |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Applique le vecteur de translation spécifié à la matrice représentée par l'objet actuel. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Multiplie chaque vecteur d'un tableau par la matrice représentée par l'objet actuel. |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Multiplie chaque vecteur d'un tableau par la matrice représentée par l'objet actuel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Matrix](./~matrix/)() | Destructeur. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |
## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [System::Drawing::Drawing2D](../)
* Bibliothèque [Aspose.Slides](../../)