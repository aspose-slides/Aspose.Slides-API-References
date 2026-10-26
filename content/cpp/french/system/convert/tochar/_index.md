---
title: ToChar()
second_title: Référence de l'API Aspose.Slides pour C++
description: La conversion n'est pas prise en charge. Lance toujours InvalidCastException.
type: docs
weight: 118
url: /fr/system/convert/tochar/
---
## Convert::ToChar(bool) méthode

La conversion n’est pas prise en charge. Lance toujours InvalidCastException.

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) méthode

Convertit l’entier non signé de 8 bits spécifié en un caractère unicode équivalent.

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) méthode

Convertit l’entier signé de 8 bits spécifié en un caractère unicode équivalent.

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) méthode

Convertit l’entier non signé de 16 bits spécifié en un caractère unicode équivalent.

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) méthode

Convertit l’entier signé de 16 bits spécifié en un caractère unicode équivalent.

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) méthode

Convertit l’entier non signé de 32 bits spécifié en un caractère unicode équivalent.

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) méthode

Convertit l’entier signé de 32 bits spécifié en un caractère unicode équivalent.

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) méthode

Convertit l’entier non signé de 64 bits spécifié en un caractère unicode équivalent.

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) méthode

Convertit l’entier signé de 64 bits spécifié en un caractère unicode équivalent.

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) méthode

La conversion n’est pas prise en charge. Lance toujours InvalidCastException.

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) méthode

La conversion n’est pas prise en charge. Lance toujours InvalidCastException.

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) méthode

La conversion n’est pas prise en charge. Lance toujours InvalidCastException.

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) méthode

Renvoie le caractère unicode spécifié.

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) méthode

La conversion n’est pas prise en charge. Lance toujours InvalidCastException.

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) méthode

Convertit le premier et le seul caractère du c-string spécifié en une valeur char_t.

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const char_t * | Le c-string à convertir ; il doit contenir exactement 1 caractère. |

### Valeur de retour

Le premier et le seul caractère du c-string spécifié s’il contient exactement 1 caractère, sinon - 0

## Convert::ToChar(const String\&) méthode

Convertit le premier et le seul caractère de la chaîne spécifiée en une valeur char_t.

```cpp
static char_t System::Convert::ToChar(const String &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir ; elle doit contenir exactement 1 caractère. |

### Valeur de retour

Le premier et le seul caractère de la chaîne spécifiée s’il contient exactement 1 caractère, sinon - 0

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit le premier et le seul caractère de la chaîne spécifiée en une valeur char_t.

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir ; elle doit contenir exactement 1 caractère. |

### Valeur de retour

Le premier et le seul caractère de la chaîne spécifiée s’il contient exactement 1 caractère, sinon - 0

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la valeur encapsulée spécifiée en un caractère unicode équivalent.

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Le pointeur partagé vers l’objet contenant la valeur à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Le format de chaîne à utiliser si le type de la valeur encapsulée est [String](../../string/) |

### Valeur de retour

Un caractère unicode équivalent à la valeur encapsulée spécifiée

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Decimal](../../decimal/)
* Classe [DateTime](../../datetime/)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [Object](../../object/)
* Structure [Convert](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)