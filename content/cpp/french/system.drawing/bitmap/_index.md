---
title: Bitmap
second_title: Référence API Aspose.Slides pour C++
description: "Représente une image bitmap GDI+. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject() . Ne jamais créer d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Toujours envelopper cette classe dans un pointeur System::SmartPtr et utiliser ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 1
url: /fr/system.drawing/bitmap/
---
## Classe Bitmap

Représente une image bitmap GDI+. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne jamais créer d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument.

```cpp
class Bitmap : public System::Drawing::Image
```

## Méthodes

| Method | Description |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | Active le mode de traitement des pixels. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | Construit un nouvel objet [Bitmap](./) à partir de l'image existante spécifiée. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | Construit un nouvel objet [Bitmap](./) à partir du flux spécifié. |
|  [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | Construit un nouvel objet [Bitmap](./) à partir du fichier spécifié. |
|  [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | Construit un nouvel objet [Bitmap](./) à partir du fichier spécifié. |
|  [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Construit un nouvel objet [Bitmap](./) qui représente une image bitmap avec la largeur, la hauteur, le format de pixel et les données de pixel spécifiés. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | Construit un nouvel objet [Bitmap](./) à partir de l'image existante spécifiée, redimensionnée à la taille spécifiée. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | Construit un nouvel objet [Bitmap](./) à partir de l'image existante spécifiée en redimensionnant la largeur et la hauteur aux valeurs spécifiées. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | Crée une copie de l'objet actuel. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Crée un objet [Bitmap](./) qui représente une copie d'une région de l'image bitmap représentée par l'objet actuel. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Crée un objet [Bitmap](./) qui représente une copie d'une région de l'image bitmap représentée par l'objet actuel. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | Calcule la valeur de hachage SHA1. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | Crée une copie de l'image bitmap spécifiée en changeant le format de pixel à Format32bppArgb. |
| void [Dispose](../image/dispose/)() override | Libère toutes les ressources acquises par l'objet actuel. |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | Désactive le mode de traitement des pixels. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | Crée un objet [Image](../image/) à partir du fichier spécifié. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | Construit un objet [Bitmap](./) à partir du bitmap GDI spécifié. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Crée un objet [Image](../image/) à partir du flux spécifié. |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | Renvoie une combinaison bit à bit des valeurs de l'énumération ImageFlags qui représente les attributs de l'image. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | Renvoie un tableau de GUID qui représentent les dimensions des images dans l'image représentée par l'objet actuel. |
| int [get_Height](./get_height/)() const override | Renvoie la hauteur de l'image en pixels. |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | Renvoie la résolution horizontale de l'image représentée par l'objet actuel, en pixels par pouce. |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | Renvoie la palette de couleurs utilisée par l'image représentée par l'objet actuel. |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | Renvoie le format de pixel de l'image représentée par l'objet actuel. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | Obtient les ID des éléments de propriété stockés dans cette image. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | Obtient tous les éléments de propriété (métadonnées) stockés dans cette image. |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | Renvoie le format de fichier de l'image représentée par l'objet actuel. |
| [Size](../size/) [get_Size](../image/get_size/)() const | Renvoie un objet [Size](../size/) qui représente la largeur et la hauteur de l'image en pixels. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | Obtient un objet qui fournit des données supplémentaires sur l'image. |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | Renvoie la résolution verticale de l'image représentée par l'objet actuel, en pixels par pouce. |
| int [get_Width](./get_width/)() const override | Renvoie la largeur de l'image en pixels. |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | Renvoie les limites de l'image dans les unités de mesure spécifiées. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | Renvoie le nombre d'images de la dimension de trame spécifiée. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| IntPtr [GetHbitmap](./gethbitmap/)() | Crée un objet bitmap GDI à partir du bitmap représenté par l'objet actuel. |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | Renvoie la couleur du pixel spécifié. |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Renvoie le nombre de bits utilisés pour représenter la profondeur de couleur dans le format de pixel spécifié. |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | Renvoie un pointeur brut vers l'objet SkBitmap sous-jacent. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | Obtient une vignette pour cet objet [System::Drawing::Image](../image/). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Détermine si le format de pixel spécifié contient des informations alpha. |
| **bool** [IsMultiImage](./ismultiimage/)() const override | Renvoie si le format original est une image multiple. |
| void [Lock](../../system/object/lock/)() | Met en œuvre le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Verrouille un [Bitmap](./) dans la mémoire du système. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Verrouille un [Bitmap](./) dans la mémoire du système. |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | Modifie la couleur de tous les pixels de la couleur spécifiée en transparent. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet de cloner des types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| void [PremultipleColors](./premultiplecolors/)() | Prémultiplie les couleurs des pixels de l'image représentée par l'objet actuel. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | Fait pivoter l'image à un multiple de 90 degrés et l'inverse. |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | Enregistre l'image représentée par l'objet actuel dans le fichier spécifié au format PNG. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Enregistre l'image représentée par l'objet actuel dans le fichier spécifié au format indiqué. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Enregistre l'image représentée par l'objet actuel dans le flux spécifié au format indiqué. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Enregistre l'image représentée par l'objet actuel dans le fichier spécifié en utilisant l'encodeur et les paramètres d'encodeur spécifiés. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Enregistre l'image représentée par l'objet actuel dans le flux spécifié en utilisant l'encodeur et les paramètres d'encodeur spécifiés. |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Ajoute une image au fichier ou au flux spécifié lors d'un appel précédent à la méthode [Save()](../image/save/). |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Ajoute une image au fichier ou au flux spécifié lors d'un appel précédent à la méthode [Save()](../image/save/). |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | Sélectionne l'image spécifiée. |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | Définit la palette de couleurs utilisée par l'image représentée par l'objet actuel. |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Définit un objet qui fournit des données supplémentaires sur l'image. |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | Définit la couleur du pixel spécifié dans l'image bitmap représentée par l'objet actuel. |
| void [SetResolution](./setresolution/)(**float**, **float**) | Définit la résolution de l'image. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le nᵉ argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs des conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Met en œuvre la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Met en œuvre le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Déverrouille le bitmap spécifié de la mémoire du système. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [Image](../image/)
* Espace de noms [System::Drawing](../)
* Bibliothèque [Aspose.Slides](../../)