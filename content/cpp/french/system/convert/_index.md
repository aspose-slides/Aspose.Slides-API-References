---
title: Convert
second_title: Référence API Aspose.Slides pour C++
description: "La structure qui contient des méthodes effectuant la conversion de valeurs d'un type vers les valeurs d'un autre type. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer les objets de ce type."
type: docs
weight: 1535
url: /fr/system/convert/
---
## Structure de conversion

La structure qui contient des méthodes effectuant la conversion de valeurs d'un type vers les valeurs d'un autre type. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe [System::SmartPtr](../smartptr/) pour gérer les objets de ce type.

```cpp
class Convert
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | NON IMPLEMENTÉ. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Décode les données encodées en base-64 représentées sous forme d'intervalle dans le tableau de caractères Unicode. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | Décode les données encodées en base-64 représentées sous forme de chaîne. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Renvoie une valeur TypeCode représentant le type de la valeur encapsulée spécifiée. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | NON IMPLEMENTÉ. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | FAUSSE implémentation NON IMPLEMENTÉE, vérifie si la valeur est nullptr. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | Encode en base-64 une plage d'éléments du tableau d'octets spécifié et stocke les données encodées sous forme d'un tableau de caractères Unicode. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | Encode en base-64 une plage d'éléments du tableau d'octets spécifié et stocke les données encodées sous forme d'un tableau de caractères Unicode. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | Encode en base-64 les éléments du tableau d'octets spécifié et renvoie les données encodées sous forme de chaîne. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | Encode en base-64 une plage d'éléments du tableau d'octets spécifié et renvoie les données encodées sous forme de chaîne. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | Encode en base-64 les éléments du tableau d'octets spécifié et renvoie les données encodées sous forme de chaîne. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | Encode en base-64 une plage d'éléments du tableau d'octets spécifié et renvoie les données encodées sous forme de chaîne. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | Renvoie la valeur booléenne spécifiée. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | Convertit l'entier non signé de 8 bits spécifié en une valeur booléenne équivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | Convertit l'entier signé de 8 bits spécifié en une valeur booléenne équivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | Convertit l'entier non signé de 16 bits spécifié en une valeur booléeenne équivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | Convertit l'entier signé de 16 bits spécifié en une valeur booléenne équivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | Convertit l'entier non signé de 32 bits spécifié en une valeur booléenne équivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | Convertit l'entier signé de 32 bits spécifié en une valeur booléenne équivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | Convertit l'entier non signé de 64 bits spécifié en une valeur booléenne équivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | Convertit l'entier signé de 64 bits spécifié en une valeur booléenne équivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | Convertit le nombre à virgule flottante spécifié en une valeur booléenne équivalente. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | Convertit le nombre double spécifié en une valeur booléenne équivalente. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | Convertit le nombre décimal spécifié en une valeur booléenne équivalente. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | Convertit la chaîne nulle spécifiée en la valeur booléenne équivalente. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | Convertit la chaîne C spécifiée en une valeur de type bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | Convertit la chaîne spécifiée en une valeur de type bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne spécifiée en une valeur de type bool. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur encapsulée spécifiée en une valeur booléenne équivalente. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | Convertit la valeur booléenne spécifiée en un entier non signé de 8 bits équivalent. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | Renvoie l'entier non signé de 8 bits spécifié. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | Convertit l'entier signé de 8 bits spécifié en un entier non signé de 8 bits équivalent. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | Convertit l'entier non signé de 16 bits spécifié en un entier non signé de 8 bits équivalent. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | Convertit l'entier signé de 16 bits spécifié en un entier non signé de 8 bits équivalent. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | Convertit l'entier non signé de 32 bits spécifié en un entier non signé de 8 bits équivalent. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | Convertit l'entier signé de 32 bits spécifié en un entier non signé de 8 bits équivalent. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | Convertit l'entier non signé de 64 bits spécifié en un entier non signé de 8 bits équivalent. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | Convertit l'entier signé de 64 bits spécifié en un entier non signé de 8 bits équivalent. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | Convertit le nombre à virgule flottante spécifié en un entier non signé de 8 bits équivalent. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | Convertit le nombre double spécifié en un entier non signé de 8 bits équivalent. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | Convertit le nombre décimal spécifié en un entier non signé de 8 bits équivalent. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | Convertit le caractère Unicode spécifié en un entier non signé de 8 bits équivalent. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | Convertit la chaîne nulle spécifiée en la valeur entière non signée de 8 bits équivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | Convertit la chaîne C contenant la représentation textuelle d'un nombre en la valeur entière non signée de 8 bits équivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière non signée de 8 bits équivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | Convertit la chaîne contenant la représentation textuelle d'un nombre dans la base spécifiée en la valeur entière non signée de 8 bits équivalente. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière non signée de 8 bits équivalente en utilisant les informations de formatage fournies. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière non signée de 8 bits équivalente en utilisant les informations de formatage et le style numérique fournis. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur encapsulée spécifiée en une valeur entière non signée de 8 bits équivalente. |
| static char_t [ToChar](./tochar/)(**bool**) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | Convertit l'entier non signé de 8 bits spécifié en un caractère Unicode équivalent. |
| static char_t [ToChar](./tochar/)(**int8_t**) | Convertit l'entier signé de 8 bits spécifié en un caractère Unicode équivalent. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | Convertit l'entier non signé de 16 bits spécifié en un caractère Unicode équivalent. |
| static char_t [ToChar](./tochar/)(**int16_t**) | Convertit l'entier signé de 16 bits spécifié en un caractère Unicode équivalent. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | Convertit l'entier non signé de 32 bits spécifié en un caractère Unicode équivalent. |
| static char_t [ToChar](./tochar/)(**int32_t**) | Convertit l'entier signé de 32 bits spécifié en un caractère Unicode équivalent. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | Convertit l'entier non signé de 64 bits spécifié en un caractère Unicode équivalent. |
| static char_t [ToChar](./tochar/)(**int64_t**) | Convertit l'entier signé de 64 bits spécifié en un caractère Unicode équivalent. |
| static char_t [ToChar](./tochar/)(**float**) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static char_t [ToChar](./tochar/)(**double**) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | Renvoie le caractère Unicode spécifié. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static char_t [ToChar](./tochar/)(const char_t *) | Convertit le premier et unique caractère de la chaîne C spécifiée en une valeur char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | Convertit le premier et unique caractère de la chaîne spécifiée en une valeur char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit le premier et unique caractère de la chaîne spécifiée en une valeur char_t. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur encapsulée spécifiée en un caractère Unicode équivalent. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | Renvoie la date et l'heure spécifiées. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | Convertit la chaîne spécifiée en une instance de la classe [DateTime](../datetime/). |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne spécifiée en une instance de la classe [DateTime](../datetime/) en utilisant les informations de formatage fournies. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur encapsulée spécifiée en une valeur [DateTime](../datetime/) équivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | Convertit la valeur booléenne spécifiée en un nombre décimal équivalent. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | Convertit l'entier non signé de 8 bits spécifié en un nombre décimal équivalent. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | Convertit l'entier signé de 8 bits spécifié en un nombre décimal équivalent. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | Convertit l'entier non signé de 16 bits spécifié en un nombre décimal équivalent. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | Convertit l'entier signé de 16 bits spécifié en un nombre décimal équivalent. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | Convertit l'entier non signé de 32 bits spécifié en un nombre décimal équivalent. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | Convertit l'entier signé de 32 bits spécifié en un nombre décimal équivalent. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | Convertit l'entier non signé de 64 bits spécifié en un nombre décimal équivalent. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | Convertit l'entier signé de 64 bits spécifié en un nombre décimal équivalent. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | Convertit le nombre à virgule flottante spécifié en un nombre décimal équivalent. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | Convertit le nombre double spécifié en un nombre décimal équivalent. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | Renvoie le nombre décimal spécifié. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | Convertit la chaîne nulle spécifiée en la valeur [Decimal](../decimal/) équivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | Convertit la chaîne C contenant la représentation textuelle d'un nombre en la valeur [Decimal](../decimal/) équivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur [Decimal](../decimal/) équivalente. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur [Decimal](../decimal/) équivalente en utilisant les informations de formatage fournies. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur [Decimal](../decimal/) équivalente en utilisant les styles numériques et les informations de formatage spécifiés. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur encapsulée spécifiée en une valeur [Decimal](../decimal/) équivalente. |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | Convertit la valeur booléenne spécifiée en un nombre à virgule flottante double précision équivalent. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | Convertit l'entier non signé de 8 bits spécifié en un nombre double précision équivalent. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | Convertit l'entier signé de 8 bits spécifié en un nombre double précision équivalent. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | Convertit l'entier non signé de 16 bits spécifié en un nombre double précision équivalent. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | Convertit l'entier signé de 16 bits spécifié en un nombre double précision équivalent. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | Convertit l'entier non signé de 32 bits spécifié en un nombre double précision équivalent. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | Convertit l'entier signé de 32 bits spécifié en un nombre double précision équivalent. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | Convertit l'entier non signé de 64 bits spécifié en un nombre double précision équivalent. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | Convertit l'entier signé de 64 bits spécifié en un nombre double précision équivalent. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | Convertit le nombre à simple précision spécifié en un nombre double précision équivalent. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | Renvoie le nombre double spécifié. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | Convertit le nombre décimal spécifié en un nombre double précision équivalent. |
| static **double** [ToDouble](./todouble/)(char_t) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | Convertit la chaîne nulle spécifiée en la valeur double précision équivalente. |
| static **double** [ToDouble](./todouble/)(const char_t *) | Convertit la chaîne C contenant la représentation textuelle d'un nombre en la valeur double précision équivalente. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur double précision équivalente. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur double précision équivalente en utilisant les informations de formatage fournies. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur double précision équivalente en utilisant les informations de formatage et le style numérique fournis. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur encapsulée spécifiée en une valeur double précision. Si le type de la valeur encapsulée est [String](../string/), le format de chaîne spécifié est utilisé lors de la conversion. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | Convertit la valeur booléenne spécifiée en un entier signé de 16 bits équivalent. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | Convertit l'entier non signé de 8 bits spécifié en un entier signé de 16 bits équivalent. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | Convertit l'entier signé de 8 bits spécifié en un entier signé de 16 bits équivalent. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | Convertit l'entier non signé de 16 bits spécifié en un entier signé de 16 bits équivalent. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | Renvoie l'entier signé de 16 bits spécifié. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | Convertit l'entier non signé de 32 bits spécifié en un entier signé de 16 bits équivalent. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | Convertit l'entier signé de 32 bits spécifié en un entier signé de 16 bits équivalent. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | Convertit l'entier non signé de 64 bits spécifié en un entier signé de 16 bits équivalent. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | Convertit l'entier signé de 64 bits spécifié en un entier signé de 16 bits équivalent. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | Convertit le nombre à virgule flottante spécifié en un entier signé de 16 bits équivalent. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | Convertit le nombre double spécifié en un entier signé de 16 bits équivalent. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | Convertit le nombre décimal spécifié en un entier signé de 16 bits équivalent. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | Convertit le caractère Unicode spécifié en un entier signé de 16 bits équivalent. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | Convertit la chaîne nulle spécifiée en la valeur entière signée de 16 bits équivalente. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | Convertit la chaîne C contenant la représentation textuelle d'un nombre en la valeur entière signée de 16 bits équivalente. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière signée de 16 bits équivalente. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | Convertit la chaîne contenant la représentation textuelle d'un nombre dans la base spécifiée en la valeur entière signée de 16 bits équivalente. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière signée de 16 bits équivalente en utilisant les informations de formatage fournies. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière signée de 16 bits équivalente en utilisant les informations de formatage et le style numérique fournis. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur encapsulée spécifiée en une valeur entière signée de 16 bits équivalente. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | Convertit la valeur booléenne spécifiée en un entier signé de 32 bits équivalent. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | Convertit l'entier non signé de 8 bits spécifié en un entier signé de 32 bits équivalent. |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | Convertit l'entier signé de 8 bits spécifié en un entier signé de 32 bits équivalent. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | Convertit l'entier non signé de 16 bits spécifié en un entier signé de 32 bits équivalent. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | Convertit l'entier signé de 16 bits spécifié en un entier signé de 32 bits équivalent. |
| static int [ToInt32](./toint32/)(**uint32_t**) | Convertit l'entier non signé de 32 bits spécifié en un entier signé de 32 bits équivalent. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | Renvoie l'entier signé de 32 bits spécifié. |
| static int [ToInt32](./toint32/)(**uint64_t**) | Convertit l'entier non signé de 64 bits spécifié en un entier signé de 32 bits équivalent. |
| static int [ToInt32](./toint32/)(**int64_t**) | Convertit l'entier signé de 64 bits spécifié en un entier signé de 32 bits équivalent. |
| static int [ToInt32](./toint32/)(**float**) | Convertit le nombre à virgule flottante spécifié en un entier signé de 32 bits équivalent. |
| static int [ToInt32](./toint32/)(**double**) | Convertit le nombre double spécifié en un entier signé de 32 bits équivalent. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | Convertit le nombre décimal spécifié en un entier signé de 32 bits équivalent. |
| static constexpr int [ToInt32](./toint32/)(char_t) | Convertit le caractère Unicode spécifié en un entier signé de 32 bits équivalent. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | Convertit la chaîne nulle spécifiée en la valeur entière de 32 bits équivalente. |
| static int [ToInt32](./toint32/)(const char_t *) | Convertit la chaîne C contenant la représentation textuelle d'un nombre en la valeur entière de 32 bits équivalente. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière de 32 bits équivalente. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | Convertit la chaîne contenant la représentation textuelle d'un nombre dans la base spécifiée en la valeur entière de 32 bits équivalente. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière de 32 bits équivalente en utilisant les informations de formatage fournies. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière de 32 bits équivalente en utilisant les informations de formatage et le style numérique fournis. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur encapsulée spécifiée en une valeur entière de 32 bits équivalente. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | Convertit la valeur booléenne spécifiée en un entier signé de 64 bits équivalent. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | Convertit l'entier non signé de 8 bits spécifié en un entier signé de 64 bits équivalent. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | Convertit l'entier signé de 8 bits spécifié en un entier signé de 64 bits équivalent. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | Convertit l'entier non signé de 16 bits spécifié en un entier signé de 64 bits équivalent. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | Convertit l'entier signé de 16 bits spécifié en un entier signé de 64 bits équivalent. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | Convertit l'entier non signé de 32 bits spécifié en un entier signé de 64 bits équivalent. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | Convertit l'entier signé de 32 bits spécifié en un entier signé de 64 bits équivalent. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | Convertit l'entier non signé de 64 bits spécifié en un entier signé de 64 bits équivalent. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | Renvoie l'entier signé de 64 bits spécifié. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | Convertit le nombre à virgule flottante spécifié en un entier signé de 64 bits équivalent. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | Convertit le nombre double spécifié en un entier signé de 64 bits équivalent. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | Convertit le nombre décimal spécifié en un entier signé de 64 bits équivalent. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | Convertit le caractère Unicode spécifié en un entier signé de 64 bits équivalent. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | Convertit la chaîne nulle spécifiée en la valeur entière signée de 64 bits équivalente. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | Convertit la chaîne C contenant la représentation textuelle d'un nombre en la valeur entière signée de 64 bits équivalente. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière signée de 64 bits équivalente. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | Convertit la chaîne contenant la représentation textuelle d'un nombre dans la base spécifiée en la valeur entière signée de 64 bits équivalente. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière signée de 64 bits équivalente en utilisant les informations de formatage fournies. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière signée de 64 bits équivalente en utilisant les informations de formatage et le style numérique fournis. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur encapsulée spécifiée en une valeur entière signée de 64 bits équivalente. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | Convertit la valeur booléenne spécifiée en un entier signé de 8 bits équivalent. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | Convertit l'entier non signé de 8 bits spécifié en un entier signé de 8 bits équivalent. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | Renvoie l'entier signé de 8 bits spécifié. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | Convertit l'entier non signé de 16 bits spécifié en un entier signé de 8 bits équivalent. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | Convertit l'entier signé de 16 bits spécifié en un entier signé de 8 bits équivalent. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | Convertit l'entier non signé de 32 bits spécifié en un entier signé de 8 bits équivalent. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | Convertit l'entier signé de 32 bits spécifié en un entier signé de 8 bits équivalent. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | Convertit l'entier non signé de 64 bits spécifié en un entier signé de 8 bits équivalent. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | Convertit l'entier signé de 64 bits spécifié en un entier signé de 8 bits équivalent. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | Convertit le nombre à virgule flottante spécifié en un entier signé de 8 bits équivalent. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | Convertit le nombre double spécifié en un entier signé de 8 bits équivalent. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | Convertit le nombre décimal spécifié en un entier signé de 8 bits équivalent. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | Convertit le caractère Unicode spécifié en un entier signé de 8 bits équivalent. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | Convertit la chaîne nulle spécifiée en la valeur entière signée de 8 bits équivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | Convertit la chaîne C contenant la représentation textuelle d'un nombre en la valeur entière de 8 bits équivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière de 8 bits équivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | Convertit la chaîne contenant la représentation textuelle d'un nombre dans la base spécifiée en la valeur entière de 8 bits équivalente. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière non signée de 8 bits équivalente en utilisant les informations de formatage fournies. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière de 8 bits équivalente en utilisant les informations de formatage et le style numérique fournis. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur encapsulée spécifiée en une valeur entière de 8 bits équivalente. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | Convertit la valeur booléenne spécifiée en un nombre à simple précision équivalent. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | Convertit l'entier non signé de 8 bits spécifié en un nombre à simple précision équivalent. |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | Convertit l'entier signé de 8 bits spécifié en un nombre à simple précision équivalent. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | Convertit l'entier non signé de 16 bits spécifié en un nombre à simple précision équivalent. |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | Convertit l'entier signé de 16 bits spécifié en un nombre à simple précision équivalent. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | Convertit l'entier non signé de 32 bits spécifié en un nombre à simple précision équivalent. |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | Convertit l'entier signé de 32 bits spécifié en un nombre à simple précision équivalent. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | Convertit l'entier non signé de 64 bits spécifié en un nombre à simple précision équivalent. |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | Convertit l'entier signé de 64 bits spécifié en un nombre à simple précision équivalent. |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | Renvoie le nombre à simple précision spécifié. |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | Convertit le nombre double précision spécifié en un nombre à simple précision équivalent. |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | Convertit le nombre décimal spécifié en un nombre à simple précision équivalent. |
| static **float** [ToSingle](./tosingle/)(char_t) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | Convertit la chaîne nulle spécifiée en la valeur à simple précision équivalente. |
| static **float** [ToSingle](./tosingle/)(const char_t *) | Convertit la chaîne C contenant la représentation textuelle d'un nombre en la valeur à simple précision équivalente. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur à simple précision équivalente. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur à simple précision équivalente en utilisant les informations de formatage fournies. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur à simple précision en utilisant les informations de formatage et le style numérique fournis. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur encapsulée spécifiée en une valeur à simple précision. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(**float**) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(**double**) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en chaîne en utilisant les informations de formatage culturelles. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en chaîne en utilisant les informations de formatage culturelles. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en chaîne en utilisant les informations de formatage culturelles. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en chaîne en utilisant les informations de formatage culturelles. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en chaîne en utilisant les informations de formatage culturelles. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en chaîne en utilisant les informations de formatage culturelles. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en chaîne en utilisant les informations de formatage culturelles. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en chaîne en utilisant les informations de formatage culturelles. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en chaîne en utilisant les informations de formatage culturelles. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en chaîne en utilisant les informations de formatage culturelles. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en chaîne en utilisant les informations de formatage culturelles. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en chaîne en utilisant les informations de formatage culturelles. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne en utilisant le format de chaîne spécifié et les informations de formatage culturelles fournies par l'objet [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne en utilisant le format de chaîne spécifié et les informations de formatage culturelles fournies par l'objet [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne en utilisant le format de chaîne spécifié et les informations de formatage culturelles fournies par l'objet [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne en utilisant le format de chaîne spécifié et les informations de formatage culturelles fournies par l'objet [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne en utilisant le format de chaîne spécifié et les informations de formatage culturelles fournies par l'objet [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne en utilisant le format de chaîne spécifié et les informations de formatage culturelles fournies par l'objet [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne en utilisant le format de chaîne spécifié et les informations de formatage culturelles fournies par l'objet [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne en utilisant le format de chaîne spécifié et les informations de formatage culturelles fournies par l'objet [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne en utilisant le format de chaîne spécifié et les informations de formatage culturelles fournies par l'objet [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne en utilisant le format de chaîne spécifié et les informations de formatage culturelles fournies par l'objet [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne en utilisant le format de chaîne spécifié et les informations de formatage culturelles fournies par l'objet [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne en utilisant le format de chaîne spécifié et les informations de formatage culturelles fournies par l'objet [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | Convertit la valeur spécifiée en chaîne. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | Convertit la valeur spécifiée en chaîne en utilisant le format de chaîne spécifié. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | Convertit le tableau de caractères Unicode spécifié en chaîne. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit le tableau de caractères Unicode spécifié en chaîne en utilisant les informations de formatage culturelles fournies par l'objet [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | Renvoie la valeur spécifiée ; aucune conversion n'est effectuée. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Renvoie la valeur spécifiée ; aucune conversion n'est effectuée. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Renvoie la valeur spécifiée ; aucune conversion n'est effectuée. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Renvoie la valeur spécifiée ; aucune conversion n'est effectuée. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | Renvoie la valeur spécifiée ; aucune conversion n'est effectuée. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Renvoie la valeur spécifiée ; aucune conversion n'est effectuée. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Renvoie la valeur spécifiée ; aucune conversion n'est effectuée. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Renvoie la valeur spécifiée ; aucune conversion n'est effectuée. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Renvoie la valeur spécifiée ; aucune conversion n'est effectuée. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | Renvoie la valeur spécifiée ; aucune conversion n'est effectuée. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | Convertit la valeur spécifiée en sa représentation sous forme de chaîne. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | Convertit la valeur entière spécifiée en sa représentation sous forme de chaîne dans la base spécifiée. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | Convertit la valeur entière spécifiée en sa représentation sous forme de chaîne dans la base spécifiée. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | Convertit la valeur entière spécifiée en sa représentation sous forme de chaîne dans la base spécifiée. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | Convertit la valeur entière spécifiée en sa représentation sous forme de chaîne dans la base spécifiée. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur encapsulée spécifiée en sa représentation sous forme de chaîne. Si le type de la valeur encapsulée est [String](../string/), le format de chaîne spécifié est utilisé lors de la conversion. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | Convertit la valeur booléenne spécifiée en un entier non signé de 16 bits équivalent. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | Convertit l'entier non signé de 8 bits spécifié en un entier non signé de 16 bits équivalent. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | Convertit l'entier signé de 8 bits spécifié en un entier non signé de 16 bits équivalent. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | Renvoie l'entier non signé de 16 bits spécifié. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | Convertit l'entier signé de 16 bits spécifié en un entier non signé de 16 bits équivalent. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | Convertit l'entier non signé de 32 bits spécifié en un entier non signé de 16 bits équivalent. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | Convertit l'entier signé de 32 bits spécifié en un entier non signé de 16 bits équivalent. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | Convertit l'entier non signé de 64 bits spécifié en un entier non signé de 16 bits équivalent. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | Convertit l'entier signé de 64 bits spécifié en un entier non signé de 16 bits équivalent. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | Convertit le nombre à virgule flottante spécifié en un entier non signé de 16 bits équivalent. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | Convertit le nombre double spécifié en un entier non signé de 16 bits équivalent. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | Convertit le nombre décimal spécifié en un entier non signé de 16 bits équivalent. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | Convertit le caractère Unicode spécifié en un entier non signé de 16 bits équivalent. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | Convertit la chaîne nulle spécifiée en la valeur entière non signée de 16 bits équivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | Convertit la chaîne C contenant la représentation textuelle d'un nombre en la valeur entière non signée de 16 bits équivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière non signée de 16 bits équivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | Convertit la chaîne contenant la représentation textuelle d'un nombre dans la base spécifiée en la valeur entière non signée de 16 bits équivalente. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière non signée de 16 bits équivalente en utilisant les informations de formatage fournies. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière non signée de 16 bits équivalente en utilisant les informations de formatage et le style numérique fournis. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur encapsulée spécifiée en une valeur entière non signée de 16 bits équivalente. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | Convertit la valeur booléenne spécifiée en un entier non signé de 32 bits équivalent. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | Convertit l'entier non signé de 8 bits spécifié en un entier non signé de 32 bits équivalent. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | Convertit l'entier signé de 8 bits spécifié en un entier non signé de 32 bits équivalent. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | Convertit l'entier non signé de 16 bits spécifié en un entier non signé de 32 bits équivalent. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | Convertit l'entier signé de 16 bits spécifié en un entier non signé de 32 bits équivalent. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | Renvoie l'entier non signé de 32 bits spécifié. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | Convertit l'entier signé de 32 bits spécifié en un entier non signé de 32 bits équivalent. |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | Convertit l'entier non signé de 64 bits spécifié en un entier non signé de 32 bits équivalent. |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | Convertit l'entier signé de 64 bits spécifié en un entier non signé de 32 bits équivalent. |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | Convertit le nombre à virgule flottante spécifié en un entier non signé de 32 bits équivalent. |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | Convertit le nombre double spécifié en un entier non signé de 32 bits équivalent. |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | Convertit le nombre décimal spécifié en un entier non signé de 32 bits équivalent. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | Convertit le caractère Unicode spécifié en un entier non signé de 32 bits équivalent. |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | Convertit la chaîne nulle spécifiée en la valeur entière non signée de 32 bits équivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | Convertit la chaîne C contenant la représentation textuelle d'un nombre en la valeur entière non signée de 32 bits équivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière non signée de 32 bits équivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | Convertit la chaîne contenant la représentation textuelle d'un nombre dans la base spécifiée en la valeur entière non signée de 32 bits équivalente. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière non signée de 32 bits équivalente en utilisant les informations de formatage fournies. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière non signée de 32 bits équivalente en utilisant les informations de formatage et le style numérique fournis. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur encapsulée spécifiée en une valeur entière non signée de 32 bits équivalente. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | Convertit la valeur booléenne spécifiée en un entier non signé de 64 bits équivalent. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | Convertit l'entier non signé de 8 bits spécifié en un entier non signé de 64 bits équivalent. |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | Convertit l'entier signé de 8 bits spécifié en un entier non signé de 64 bits équivalent. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | Convertit l'entier non signé de 16 bits spécifié en un entier non signé de 64 bits équivalent. |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | Convertit l'entier signé de 16 bits spécifié en un entier non signé de 64 bits équivalent. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | Convertit l'entier non signé de 32 bits spécifié en un entier non signé de 64 bits équivalent. |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | Convertit l'entier signé de 32 bits spécifié en un entier non signé de 64 bits équivalent. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | Renvoie l'entier non signé de 64 bits spécifié. |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | Convertit l'entier signé de 64 bits spécifié en un entier non signé de 64 bits équivalent. |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | Convertit le nombre à virgule flottante spécifié en un entier non signé de 64 bits équivalent. |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | Convertit le nombre double spécifié en un entier non signé de 64 bits équivalent. |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | Convertit le nombre décimal spécifié en un entier non signé de 64 bits équivalent. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | Convertit le caractère Unicode spécifié en un entier non signé de 64 bits équivalent. |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | Conversion non prise en charge. Lance toujours InvalidCastException. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | Convertit la chaîne nulle spécifiée en la valeur entière non signée de 64 bits équivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | Convertit la chaîne C contenant la représentation textuelle d'un nombre en la valeur entière non signée de 64 bits équivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière non signée de 64 bits équivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | Convertit la chaîne contenant la représentation textuelle d'un nombre dans la base spécifiée en la valeur entière non signée de 64 bits équivalente. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière non signée de 64 bits équivalente en utilisant les informations de formatage fournies. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la chaîne contenant la représentation textuelle d'un nombre en la valeur entière non signée de 64 bits équivalente en utilisant les informations de formatage et le style numérique fournis. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la valeur encapsulée spécifiée en une valeur entière non signée de 64 bits équivalente. |

## Voir aussi

* Namespace [System](../)
* Library [Aspose.Slides](../../)