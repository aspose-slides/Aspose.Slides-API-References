---
title: ISVGOptions
second_title: Référence API Aspose.Slides pour C++
description: Représente des options SVG.
type: docs
weight: 404
url: /fr/aspose.slides.export/isvgoptions/
---
## ISVGOptions classe


Représente des options SVG.

```cpp
class ISVGOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante à la C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante à la C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Renvoie la police utilisée lorsque la police source n’est pas trouvée. Lit [System::String](../../system/string/). |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | Un indicateur booléen indique si les parties rognées restent dans le document. Si vrai, les parties rognées seront supprimées, si faux elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un fichier plus volumineux). Lecture **bool**. |
| virtual **bool** [get_Disable3DText](./get_disable3dtext/)() | Détermine si le texte 3D est désactivé dans le SVG. Lecture **bool**. |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | Obtient une valeur indiquant si le texte est rendu sans ligatures. Lorsque **true**, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété vaut **false**. |
| virtual **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() | Désactive le fractionnement des dégradés FromCornerX et FromCenter. Lecture **bool**. |
| virtual **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() | SVG 1.1 ne permet pas de définir des retraits pour les marqueurs. [Aspose.Slides](../../aspose.slides/) le moteur d’écriture SVG a un contournement : il recadre la fin de ligne avec la flèche, ainsi la ligne ne chevauche pas les marqueurs. Cette option désactive ce comportement. Lecture **bool**. |
| virtual [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() | Détermine la façon de gérer les polices chargées extérieurement. Lecture [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Renvoie le style visuel du dégradé. Lecture [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | Fournit des options qui contrôlent l’apparence des objets [Ink](../../aspose.slides.ink/) dans le document exporté. Lecture seule [IInkOptions](../iinkoptions/) |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Détermine la qualité d’encodage JPEG. Lecture **int32_t**. |
| virtual **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() | Renvoie la limite de résolution inférieure pour la rasterisation des métaphores. Lecture **int32_t**. |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | Représente le niveau de compression des images. Lecture [PicturesCompression](../picturescompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Représente un objet de rappel pour enregistrer les mises à jour de progression en pourcentage. Voir [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() | Renvoie et définit une interface de rappel qui permet à l’utilisateur de contrôler la conversion des formes. Lecture [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Spécifie s’il faut ignorer les hyperliens avec des appels JavaScript lors de l’enregistrement de la présentation. Lecture **bool**. La valeur par défaut est **false**. |
| virtual **bool** [get_UseFrameRotation](./get_useframerotation/)() | Détermine s’il faut effectuer la rotation spécifiée de la forme lors du rendu ou non. Lecture **bool**. La valeur par défaut est **true**. |
| virtual **bool** [get_UseFrameSize](./get_useframesize/)() | Détermine si le cadre de texte sera inclus dans la zone de rendu ou non. Lecture **bool**. La valeur par défaut est **false**. |
| virtual **bool** [get_VectorizeText](./get_vectorizetext/)() | Détermine si le texte sur une diapositive sera enregistré sous forme graphique. Lecture **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Renvoie un objet qui reçoit les avertissements et décide si le processus de chargement doit continuer ou être abandonné. Lecture [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d’objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# `is`. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, initialise simplement un nouvel objet et permet la copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, initialise simplement un nouvel objet et permet la copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre indiqué. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Définit la police utilisée lorsque la police source n’est pas trouvée. Écrit [System::String](../../system/string/). |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | Un indicateur booléen indique si les parties rognées restent dans le document. Si vrai, les parties rognées seront supprimées, si faux elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un fichier plus volumineux). Écriture **bool**. |
| virtual void [set_Disable3DText](./set_disable3dtext/)(**bool**) | Détermine si le texte 3D est désactivé dans le SVG. Écriture **bool**. |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | Définit une valeur indiquant si le texte est rendu sans ligatures. Lorsque **true**, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété vaut **false**. |
| virtual void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) | Désactive le fractionnement des dégradés FromCornerX et FromCenter. Écriture **bool**. |
| virtual void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) | SVG 1.1 ne permet pas de définir des retraits pour les marqueurs. [Aspose.Slides](../../aspose.slides/) le moteur d’écriture SVG a un contournement : il recadre la fin de ligne avec la flèche, ainsi la ligne ne chevauche pas les marqueurs. Cette option désactive ce comportement. Écriture **bool**. |
| virtual void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) | Détermine la façon de gérer les polices chargées extérieurement. Écriture [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Définit le style visuel du dégradé. Écriture [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Détermine la qualité d’encodage JPEG. Écriture **int32_t**. |
| virtual void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) | Définit la limite de résolution inférieure pour la rasterisation des métaphores. Écriture **int32_t**. |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | Représente le niveau de compression des images. Écriture [PicturesCompression](../picturescompression/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Représente un objet de rappel pour enregistrer les mises à jour de progression en pourcentage. Voir [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) | Renvoie et définit une interface de rappel qui permet à l’utilisateur de contrôler la conversion des formes. Écriture [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Spécifie s’il faut ignorer les hyperliens avec des appels JavaScript lors de l’enregistrement de la présentation. Écriture **bool**. La valeur par défaut est **false**. |
| virtual void [set_UseFrameRotation](./set_useframerotation/)(**bool**) | Détermine s’il faut effectuer la rotation spécifiée de la forme lors du rendu ou non. Écriture **bool**. La valeur par défaut est **true**. |
| virtual void [set_UseFrameSize](./set_useframesize/)(**bool**) | Détermine si le cadre de texte sera inclus dans la zone de rendu ou non. Écriture **bool**. La valeur par défaut est **false**. |
| virtual void [set_VectorizeText](./set_vectorizetext/)(**bool**) | Détermine si le texte sur une diapositive sera enregistré sous forme graphique. Écriture **bool**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Définit un objet qui reçoit les avertissements et décide si le processus de chargement doit continuer ou être abandonné. Écriture [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d’objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |
## Voir aussi

* Classe [ISaveOptions](../isaveoptions/)
* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)