---
title: Encoding
second_title: Référence de l'API Aspose.Slides pour C++
description: Services d'encodage.
type: docs
weight: 222
url: /fr/system.text/encoding/
---
## Encoding classe

[Encoding](./) services.

```cpp
class Encoding : public System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | Clône l'objet d'encodage. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Convertit les octets entre deux encodages. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Convertit les octets entre deux encodages. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compare les encodages. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante double de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | Obtient l'encodage ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | Obtient l'objet d'encodage Unicode big-endian standard. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | Obtient l'objet d'encodage UTF-32 big-endian standard. |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | Obtient le nom d'encodage compatible avec le corps du client de messagerie. |
| virtual int [get_CodePage](./get_codepage/)() | Obtient l'ID de la page de codes [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | Obtient le repli du décodage. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | Obtient l'encodage par défaut. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | Obtient le repli de l'encodage. |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | Obtient le nom d'encodage lisible par l'homme. |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | Obtient le nom d'encodage compatible avec l'en-tête du client de messagerie. |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | Vérifie si l'encodage peut être utilisé dans un navigateur pour afficher le contenu. |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | Vérifie si l'encodage peut être utilisé dans un navigateur pour sauvegarder le contenu. |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | Vérifie si l'encodage peut être utilisé dans un client de messagerie pour afficher le contenu. |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | Vérifie si l'encodage peut être utilisé dans un client de messagerie pour sauvegarder le contenu. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Vérifie si l'encodage est en lecture seule. |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | Vérifie si l'encodage est à octet unique. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | Obtient l'encodage Latin1. POUR USAGE INTERNE. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | Obtient l'objet d'encodage Unicode standard. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | Obtient l'objet d'encodage UTF-7 standard. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | Obtient l'objet d'encodage UTF-8 standard. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | Réservé à un usage interne, à être utilisé par les bibliothèques de classes : non marqué et ne valide pas l'entrée. |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | Obtient le nom d'encodage compatible IANA. |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | Obtient l'ID de la page de codes [Windows](../../system.windows/). |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Obtient le nombre de caractères nécessaires pour encoder un tampon de caractères. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Obtient le nombre de caractères nécessaires pour encoder un tampon de caractères. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Obtient le nombre de caractères nécessaires pour encoder un tampon de caractères. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Obtient le nombre de caractères nécessaires pour encoder une chaîne. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Obtient le nombre de caractères nécessaires pour encoder un tampon de caractères. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Obtient le nombre de caractères nécessaires pour encoder un tampon de caractères. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Obtient les octets résultant de l'encodage d'un tampon de caractères. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Obtient les octets résultant de l'encodage d'un tampon de caractères. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Obtient les octets résultant de l'encodage d'un tampon de caractères. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Obtient les octets résultant de l'encodage d'un tampon de caractères. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Obtient les octets résultant de l'encodage d'un tampon de caractères. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Obtient les octets résultant de l'encodage d'un tampon de caractères. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Obtient les octets résultant de l'encodage d'un tampon de caractères. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Obtient les octets résultant de l'encodage d'un tampon de caractères. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Obtient les octets résultant de l'encodage d'un tampon de caractères. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Obtient les octets résultant de l'encodage d'un tampon de caractères. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Obtient le nombre de caractères nécessaires pour décoder un tampon d'octets. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Obtient le nombre de caractères nécessaires pour décoder un tampon d'octets. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Obtient le nombre de caractères nécessaires pour décoder un tampon d'octets. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Obtient les caractères résultant du décodage d'un tampon d'octets. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Obtient les caractères résultant du décodage d'un tampon d'octets. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Obtient les caractères résultant du décodage d'un tampon d'octets. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Obtient les caractères résultant du décodage d'un tampon d'octets. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | Obtient un décodeur qui transmet les requêtes à cet objet. |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | Obtient un encodeur qui transmet les requêtes à cet objet. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | Obtient l'encodage par nom. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | Obtient l'encodage par page de codes. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Obtient l'encodage par page de codes. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Obtient l'encodage par nom. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | Obtient la liste des encodages connus. |
| int [GetHashCode](./gethashcode/)() const override | Hash l'encodage. |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | Obtient le nombre maximal d'octets nécessaires pour encoder un nombre spécifié de caractères. |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | Obtient le nombre maximal de caractères nécessaires pour décoder un nombre spécifié d'octets. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | Renvoie une séquence d'octets qui désigne l'encodage (par ex. BOM). |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Décode un tampon d'octets en une chaîne. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Décode un tampon d'octets en une chaîne. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Décode un tampon d'octets en une chaîne. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Décode un tampon d'octets en une chaîne. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Décode un tampon d'octets en une chaîne. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Décode un tampon d'octets en une chaîne. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Décode un tampon d'octets en une chaîne. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Décode un tampon d'octets en une chaîne. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Met en œuvre le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Définit le repli du décodage. |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Définit le repli de l'encodage. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le nᵉ argument de modèle comme un pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Met en œuvre le construct typeof([System.Object](../../system/object/)) de C#. |
| void [Unlock](../../system/object/unlock/)() | Met en œuvre le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Champs

| Champ | Description |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | Valeur de page de codes par défaut. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [System::Text](../)
* Bibliothèque [Aspose.Slides](../../)