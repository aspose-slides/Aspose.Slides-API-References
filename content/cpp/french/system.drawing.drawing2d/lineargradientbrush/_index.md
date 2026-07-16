---
title: LinearGradientBrush
second_title: Référence API Aspose.Slides pour C++
description: "Représente un pinceau à dégradé linéaire. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument."
type: docs
weight: 105
url: /fr/system.drawing.drawing2d/lineargradientbrush/
---
## LinearGradientBrush classe


Représente un pinceau à dégradé linéaire. Les objets de cette classe doivent uniquement être alloués en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d’instance de ce type sur la pile ou avec l’opérateur new, car cela provoquerait des erreurs d’exécution et/ou des échecs d’assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu’argument.

```cpp
class LinearGradientBrush : public System::Drawing::Brush
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Crée une copie de l'objet actuel. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Ne fait rien. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\> [get_Blend](./get_blend/)() const | Renvoie un mélange qui spécifie les facteurs et les positions des couleurs de base pour ce pinceau. |
| **bool** [get_GammaCorrection](./get_gammacorrection/)() const | Renvoie une valeur indiquant que la correction gamma est activée pour ce pinceau. |
| [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\> [get_InterpolationColors](./get_interpolationcolors/)() const | Renvoie un objet [ColorBlend](../colorblend/) qui définit un dégradé linéaire multicolore. |
| [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\> [get_LinearColors](./get_linearcolors/)() const | Renvoie les couleurs de départ et de fin de ce dégradé. |
| [RectangleF](../../system.drawing/rectanglef/) [get_Rectangle](./get_rectangle/)() | Renvoie un rectangle englobant. |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\> [get_Transform](./get_transform/)() const | Renvoie une copie d'un objet [Matrix](../matrix/) qui spécifie les transformations géométriques du pinceau représenté par l'objet actuel. |
| [WrapMode](../wrapmode/) [get_WrapMode](./get_wrapmode/)() const | Renvoie le mode d'enveloppement. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
|  [LinearGradientBrush](./lineargradientbrush/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&) | Construit une nouvelle instance de [LinearGradientBrush](./). |
|  [LinearGradientBrush](./lineargradientbrush/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&) | Construit une nouvelle instance de [LinearGradientBrush](./). |
|  [LinearGradientBrush](./lineargradientbrush/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, [LinearGradientMode](../lineargradientmode/)) | Construit une nouvelle instance de [LinearGradientBrush](./). |
|  [LinearGradientBrush](./lineargradientbrush/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, [LinearGradientMode](../lineargradientmode/)) | Construit une nouvelle instance de [LinearGradientBrush](./). |
|  [LinearGradientBrush](./lineargradientbrush/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, **float**, **bool**) | Construit une nouvelle instance de [LinearGradientBrush](./). |
|  [LinearGradientBrush](./lineargradientbrush/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, **float**, **bool**) | Construit une nouvelle instance de [LinearGradientBrush](./). |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&, [MatrixOrder](../matrixorder/)) | Multiplie la matrice de transformation de l'objet courant par la matrice spécifiée. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classements. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classements. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [ResetTransform](./resettransform/)() | Réinitialise la matrice de transformation de l'objet courant. |
| void [RotateTransform](./rotatetransform/)(**float**, [MatrixOrder](../matrixorder/)) | Fait pivoter la matrice de transformation de l'objet courant. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Met à l’échelle la matrice de transformation de l'objet courant. |
| void [set_Blend](./set_blend/)(const [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\>\&) | Définit un mélange qui spécifie les facteurs et les positions des couleurs de base pour ce pinceau. |
| void [set_GammaCorrection](./set_gammacorrection/)(**bool**) | Définit l’état de la correction gamma pour ce pinceau. |
| void [set_InterpolationColors](./set_interpolationcolors/)(const [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\>\&) | Définit un objet [ColorBlend](../colorblend/) qui définit un dégradé linéaire multicolore. |
| void [set_LinearColors](./set_linearcolors/)(const [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\>\&) | Définit les couleurs de départ et de fin de ce dégradé. |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&) | Définit un objet [Matrix](../matrix/) qui spécifie les transformations géométriques du pinceau représenté par l'objet actuel. |
| void [set_WrapMode](./set_wrapmode/)([WrapMode](../wrapmode/)) | Définit le mode d'enveloppement. |
| void [SetBlendTriangularShape](./setblendtriangularshape/)(**float**, **float**) | NON IMPLEMÉNTÉ. |
| void [SetSigmaBellShape](./setsigmabellshape/)(**float**, **float**) | NON IMPLEMÉNTÉ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | Déplace la matrice de transformation de l'objet courant. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [Brush](../../system.drawing/brush/)
* Espace de noms [System::Drawing::Drawing2D](../)
* Bibliothèque [Aspose.Slides](../../)