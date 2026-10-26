---
title: ISwfOptions
second_title: Référence de l'API Aspose.Slides pour C++
description: Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format SWF.
type: docs
weight: 469
url: /fr/aspose.slides.export/iswfoptions/
---
## ISwfOptions classe

Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format SWF.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante à la manière de C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante à la manière de C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual **bool** [get_Compressed](./get_compressed/)() | Spécifie si le document SWF généré doit être compressé ou non. La valeur par défaut est **true**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Retourne la police utilisée si la police source n'est pas trouvée. Lit [System::String](../../system/string/). |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | Active/désactive le menu contextuel. La valeur par défaut est **true**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Retourne le style visuel du dégradé. Lit [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Spécifie la qualité des images JPEG.\n\nLa valeur par défaut est 95. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | Image qui sera affichée comme logo dans le coin supérieur droit du visualiseur.\n\nL'image doit être un PNG de 32x64 pixels, sinon le logo peut s'afficher de manière incorrecte. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | Obtient l'adresse hypertexte complète d'un logo. N'a d'effet que si un [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) est spécifié. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Représente un objet de rappel pour enregistrer les mises à jour de progression en pourcentage. Voir [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | Affiche/masque le volet inférieur. Peut être remplacé dans les flashvars. La valeur par défaut est **true**. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | Affiche/masque le bouton plein écran. Peut être remplacé dans les flashvars. La valeur par défaut est **true**. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Spécifie si le document généré doit inclure les diapositives cachées ou non. La valeur par défaut est **false**. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | Affiche/masque le volet gauche. Peut être remplacé dans les flashvars. La valeur par défaut est **true**. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | Spécifie si la bordure autour des pages doit être affichée. La valeur par défaut est **true**. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | Affiche/masque le sélecteur de page. Peut être remplacé dans les flashvars. La valeur par défaut est **true**. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | Affiche/masque la section de recherche. Peut être remplacé dans les flashvars. La valeur par défaut est **true**. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | Affiche/masque l'ensemble du volet supérieur. Peut être remplacé dans les flashvars. La valeur par défaut est **true**. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Spécifie s'il faut ignorer les hyperliens contenant des appels JavaScript lors de l'enregistrement de la présentation. Lit **bool**. La valeur par défaut est **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Obtient le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../islideslayoutoptions/). Cette propriété ne prend pas en charge l'affectation d'objets de type **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | Démarre avec le volet gauche ouvert. Peut être remplacé dans les flashvars. La valeur par défaut est **false**. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | Spécifie si le document SWF généré doit inclure le visualiseur de document intégré ou non. La valeur par défaut est **true**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Retourne un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être interrompu. Lit [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, vraiment, il initialise simplement un nouvel objet et autorise la construction de copies des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, vraiment, il initialise simplement un nouvel objet et autorise la construction de copies des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | Spécifie si le document SWF généré doit être compressé ou non. La valeur par défaut est **true**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Définit la police utilisée si la police source n'est pas trouvée. Écrit [System::String](../../system/string/). |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | Active/désactive le menu contextuel. La valeur par défaut est **true**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Définit le style visuel du dégradé. Écrit [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Spécifie la qualité des images JPEG.\n\nLa valeur par défaut est 95. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Image qui sera affichée comme logo dans le coin supérieur droit du visualiseur.\n\nL'image doit être un PNG de 32x64 pixels, sinon le logo peut s'afficher de manière incorrecte. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | Définit l'adresse hypertexte complète d'un logo. N'a d'effet que si un [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) est spécifié. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Représente un objet de rappel pour enregistrer les mises à jour de progression en pourcentage. Voir [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | Affiche/masque le volet inférieur. Peut être remplacé dans les flashvars. La valeur par défaut est **true**. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | Affiche/masque le bouton plein écran. Peut être remplacé dans les flashvars. La valeur par défaut est **true**. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Spécifie si le document généré doit inclure les diapositives cachées ou non. La valeur par défaut est **false**. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | Affiche/masque le volet gauche. Peut être remplacé dans les flashvars. La valeur par défaut est **true**. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | Spécifie si la bordure autour des pages doit être affichée. La valeur par défaut est **true**. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | Affiche/masque le sélecteur de page. Peut être remplacé dans les flashvars. La valeur par défaut est **true**. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | Affiche/masque la section de recherche. Peut être remplacé dans les flashvars. La valeur par défaut est **true**. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | Affiche/masque l'ensemble du volet supérieur. Peut être remplacé dans les flashvars. La valeur par défaut est **true**. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Spécifie s'il faut ignorer les hyperliens contenant des appels JavaScript lors de l'enregistrement de la présentation. Écrit **bool**. La valeur par défaut est **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../islideslayoutoptions/). Cette propriété ne prend pas en charge l'affectation d'objets de type **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | Démarre avec le volet gauche ouvert. Peut être remplacé dans les flashvars. La valeur par défaut est **false**. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | Spécifie si le document SWF généré doit inclure le visualiseur de document intégré ou non. La valeur par défaut est **true**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être interrompu. Écrit [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le nᵉᵉ argument de modèle comme pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [ISaveOptions](../isaveoptions/)
* Espace de noms [Aspose::Slides::Export](../)
* Bibliothèque [Aspose.Slides](../../)