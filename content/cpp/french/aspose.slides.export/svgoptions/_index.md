---
title: SVGOptions
second_title: Référence API Aspose.Slides pour C++
description: Représente des options SVG.
type: docs
weight: 703
url: /fr/aspose.slides.export/svgoptions/
---
## SVGOptions classe

Represents an SVG options.

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, le NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, le NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | Renvoie les paramètres par défaut. Lecture seule [SVGOptions](./). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Renvoie la police utilisée si la police source est introuvable. Lit [System::String](../../system/string/). |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | Un drapeau booléen indique si les parties découpées restent dans le document. Si vrai, les parties découpées seront supprimées, si faux elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un fichier plus volumineux). |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | Détermine si le texte 3D est désactivé dans SVG. Lecture **bool**. |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | Obtient une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsqu’elle est définie sur **true**, les ligatures seront désactivées dans le rendu. Par défaut, cette propriété est définie sur **false**. |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | Désactive la division des dégradés FromCornerX et FromCenter. Lecture **bool**. |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | SVG 1.1 ne permet pas de définir des retraits pour les marqueurs. [Aspose.Slides](../../aspose.slides/) le moteur d’écriture SVG possède une solution de contournement : il recadre la fin de ligne avec la flèche, de sorte que la ligne ne chevauche pas les marqueurs. Cette option désactive ce comportement. Lecture **bool**. |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | Détermine une méthode de gestion des polices chargées externement. Lecture [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Renvoie le style visuel du dégradé. Lecture [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Fournit des options qui contrôlent l’apparence des objets [Ink](../../aspose.slides.ink/) dans le document exporté. Lecture seule [IInkOptions](../iinkoptions/) |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Détermine la qualité d’encodage JPEG. Lecture **int32_t**. |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | Renvoie la limite de résolution basse pour la rasterisation de métafichier. Lecture **int32_t**. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | Représente le niveau de compression des images |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Représente un objet de rappel pour enregistrer les mises à jour de progression en pourcentage. Voir [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | Renvoie et définit une interface de rappel qui permet à l’utilisateur de contrôler la conversion de forme. Lecture [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | Renvoie les paramètres pour la génération du fichier SVG le plus simple et le plus petit. Lecture seule [SVGOptions](./). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Spécifie s’il faut ignorer les hyperliens avec des appels JavaScript lors de l’enregistrement de la présentation. Lecture **bool**. La valeur par défaut est **false**. |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | Détermine s’il faut effectuer la rotation spécifiée de la forme lors du rendu ou non. Lecture **bool**. La valeur par défaut est true. |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | Détermine si le cadre de texte sera inclus dans la zone de rendu ou non. Lecture **bool**. La valeur par défaut est false. |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | Détermine si le texte d’une diapositive sera enregistré comme graphique. Lecture **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement se poursuivra ou sera interrompu. Lecture [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | Renvoie les paramètres pour la génération du fichier SVG la plus précise. Lecture seule [SVGOptions](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d’objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie en fait rien, il initialise simplement un nouvel objet et permet de copier les sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie en fait rien, il initialise simplement un nouvel objet et permet de copier les sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Définit la police utilisée si la police source est introuvable. Écrit [System::String](../../system/string/). |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | Un drapeau booléen indique si les parties découpées restent dans le document. Si vrai, les parties découpées seront supprimées, si faux elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un fichier plus volumineux). |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | Détermine si le texte 3D est désactivé dans SVG. Écrit **bool**. |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | Définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsqu’elle est définie sur **true**, les ligatures seront désactivées dans le rendu. Par défaut, cette propriété est définie sur **false**. |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | Désactive la division des dégradés FromCornerX et FromCenter. Écrit **bool**. |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | SVG 1.1 ne permet pas de définir des retraits pour les marqueurs. [Aspose.Slides](../../aspose.slides/) le moteur d’écriture SVG possède une solution de contournement : il recadre la fin de ligne avec la flèche, ainsi la ligne ne chevauche pas les marqueurs. Cette option désactive ce comportement. Écrit **bool**. |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | Détermine une méthode de gestion des polices chargées externement. Écrit [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Définit le style visuel du dégradé. Écrit [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Détermine la qualité d’encodage JPEG. Écrit **int32_t**. |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | Définit la limite de résolution basse pour la rasterisation de métafichier. Écrit **int32_t**. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | Représente le niveau de compression des images |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Représente un objet de rappel pour enregistrer les mises à jour de progression en pourcentage. Voir [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | Renvoie et définit une interface de rappel qui permet à l’utilisateur de contrôler la conversion de forme. Écrit [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Spécifie s’il faut ignorer les hyperliens avec des appels JavaScript lors de l’enregistrement de la présentation. Écrit **bool**. La valeur par défaut est **false**. |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | Détermine s’il faut effectuer la rotation spécifiée de la forme lors du rendu ou non. Écrit **bool**. La valeur par défaut est true. |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | Détermine si le cadre de texte sera inclus dans la zone de rendu ou non. Écrit **bool**. La valeur par défaut est false. |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | Détermine si le texte d’une diapositive sera enregistré comme graphique. Écrit **bool**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement se poursuivra ou sera interrompu. Écrit [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
|  [SVGOptions](./svgoptions/)() | Initialise une nouvelle instance de la classe [SVGOptions](./). |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | Initialise une nouvelle instance de la classe [SVGOptions](./) en spécifiant l’objet contrôleur d’insertion de lien. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [SaveOptions](../saveoptions/)
* Classe [ISVGOptions](../isvgoptions/)
* Espace de noms [Aspose::Slides::Export](../)
* Bibliothèque [Aspose.Slides](../../)