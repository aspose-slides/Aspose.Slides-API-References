---
title: PdfOptions
second_title: Référence API Aspose.Slides pour C++
description: Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format Pdf.
type: docs
weight: 573
url: /fr/aspose.slides.export/pdfoptions/
---
## PdfOptions classe

Provides options that control how a presentation is saved in Pdf format.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | Contient un ensemble de drapeaux spécifiant les autorisations d'accès à accorder lorsque le document est ouvert avec un accès utilisateur. Voir [PdfAccessPermissions](../pdfaccesspermissions/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | Renvoie un tableau de noms de familles de polices définis par l'utilisateur que [Aspose.Slides](../../aspose.slides/) doit considérer comme communes. Lire [System::String](../../system/string/)[]. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | Applique la couleur transparente spécifiée à une image si **true**. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée automatiquement. Si réglé sur **bool**.true, pour chaque image de la présentation l'algorithme de compression le plus approprié sera choisi, ce qui conduira à une taille plus petite du document PDF résultat. |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | Niveau de conformité souhaité pour le document PDF généré. Lire [PdfCompliance](../pdfcompliance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Renvoie la police utilisée si la police source n'est pas trouvée. Lire [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | Vrai pour dessiner un cadre noir autour de chaque diapositive. Lire **bool**. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | Détermine si tous les caractères de la police doivent être incorporés ou seulement un sous-ensemble utilisé. Lire **bool**. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | Détermine si [Aspose.Slides](../../aspose.slides/) incorporera les polices communes pour le texte ASCII (plage de codes 33..127). [Fonts](../../aspose.slides/fonts/) pour les codes de caractères supérieurs à 127 sont toujours incorporés. La liste des polices communes comprend les 14 polices de base du PDF et des polices supplémentaires spécifiées par l'utilisateur. Lire **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Renvoie le style visuel du gradient. Lire [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | Obtient la couleur transparente de l'image. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | Vrai pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. Lire **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Fournit des options qui contrôlent l'apparence des objets [Ink](../../aspose.slides.ink/) dans le document exporté. Lecture seule [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | Renvoie une valeur déterminant la qualité des images JPEG à l'intérieur du document PDF. Lire **uint8_t**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Définition du mot de passe utilisateur pour protéger le document PDF. Lire [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Représente un objet de rappel pour la sauvegarde des mises à jour de progression en pourcentage. Voir [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | Indique si le texte doit être rasterisé en bitmap et enregistré dans le PDF lorsque la police ne prend pas en charge le style gras. Cette approche peut améliorer la qualité du texte dans le PDF résultant pour certaines polices. Lire **bool**. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Lire **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Spécifie s'il faut ignorer les hyperliens avec des appels JavaScript lors de la sauvegarde de la présentation. Lire **bool**. La valeur par défaut est **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Obtient le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | Renvoie une valeur déterminant la résolution des images à l'intérieur du document PDF. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | Spécifie le type de compression à utiliser pour tout le contenu textuel du document. Lire [PdfTextCompression](../pdftextcompression/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement continue ou est interrompu. Lire [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie en fait rien, il initialise simplement le nouvel objet et permet la construction de copies des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie en fait rien, il initialise simplement le nouvel objet et permet la construction de copies des sous-classes. |
|  [PdfOptions](./pdfoptions/)() | Constructeur par défaut. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | Contient un ensemble de drapeaux spécifiant les autorisations d'accès à accorder lorsque le document est ouvert avec un accès utilisateur. Voir [PdfAccessPermissions](../pdfaccesspermissions/). |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Définit un tableau de noms de familles de polices définis par l'utilisateur que [Aspose.Slides](../../aspose.slides/) doit considérer comme communes. Écrire [System::String](../../system/string/)[]. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | Applique la couleur transparente spécifiée à une image si **true**. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée automatiquement. Si réglé sur **bool**.true, pour chaque image de la présentation l'algorithme de compression le plus approprié sera choisi, ce qui conduira à une taille plus petite du document PDF résultat. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | Niveau de conformité souhaité pour le document PDF généré. Écrire [PdfCompliance](../pdfcompliance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Définit la police utilisée si la police source n'est pas trouvée. Écrit [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | Vrai pour dessiner un cadre noir autour de chaque diapositive. Écrire **bool**. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | Détermine si tous les caractères de la police doivent être incorporés ou seulement un sous-ensemble utilisé. Écrire **bool**. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | Détermine si [Aspose.Slides](../../aspose.slides/) incorporera les polices communes pour le texte ASCII (plage de codes 33..127). [Fonts](../../aspose.slides/fonts/) pour les codes de caractères supérieurs à 127 sont toujours incorporés. La liste des polices communes comprend les 14 polices de base du PDF et des polices supplémentaires spécifiées par l'utilisateur. Écrire **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Définit le style visuel du gradient. Écrire [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | Définit la couleur transparente de l'image. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | Vrai pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. Écrire **bool**. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | Définit une valeur déterminant la qualité des images JPEG à l'intérieur du document PDF. Écrire **uint8_t**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Définition du mot de passe utilisateur pour protéger le document PDF. Écrire [System::String](../../system/string/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Représente un objet de rappel pour la sauvegarde des mises à jour de progression en pourcentage. Voir [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | Indique si le texte doit être rasterisé en bitmap et enregistré dans le PDF lorsque la police ne prend pas en charge le style gras. Cette approche peut améliorer la qualité du texte dans le PDF résultant pour certaines polices. Écrire **bool**. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Écrire **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Spécifie s'il faut ignorer les hyperliens avec des appels JavaScript lors de la sauvegarde de la présentation. Écrire **bool**. La valeur par défaut est **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | Définit une valeur déterminant la résolution des images à l'intérieur du document PDF. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | Spécifie le type de compression à utiliser pour tout le contenu textuel du document. Écrire [PdfTextCompression](../pdftextcompression/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement continue ou est interrompu. Écrire [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs vers le mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Remarques

L'exemple suivant montre comment convertir un PowerPoint en PDF avec des options personnalisées.
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Instancie la classe PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Définit la qualité JPEG
pdfOptions->set_JpegQuality(90);
// Définit le comportement des métafichiers
pdfOptions->set_SaveMetafilesAsPng(true);
// Définit le niveau de compression du texte
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// Définit la norme PDF
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// Enregistre la présentation au format PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
L'exemple suivant montre comment convertir un PowerPoint en PDF avec des diapositives masquées.
```cpp
// Instancie une classe Presentation qui représente un fichier PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Instancie la classe PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Ajoute les diapositives masquées
pdfOptions->set_ShowHiddenSlides(true);
// Enregistre la présentation au format PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
L'exemple suivant montre comment convertir un PowerPoint en PDF avec un PDF protégé par mot de passe.
```cpp
// Instancie un objet Presentation qui représente un fichier PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// Définit le mot de passe PDF et les autorisations d'accès
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// Enregistre la présentation au format PDF
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
L'exemple suivant montre comment convertir un PowerPoint en PDF avec des notes.
```cpp
// Instancie un objet Presentation qui représente un fichier de présentation
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Setting Slide Type and Size
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## Voir aussi

* Classe [SaveOptions](../saveoptions/)
* Classe [IPdfOptions](../ipdfoptions/)
* Espace de noms [Aspose::Slides::Export](../)
* Bibliothèque [Aspose.Slides](../../)