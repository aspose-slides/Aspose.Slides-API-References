---
title: ToBase64String()
second_title: Aspose.Slides C++ API-referencia
description: A Base-64 kódolja a megadott bájttömbben lévő elemeket, és a kódolt adatot karakterláncként adja vissza.
type: docs
weight: 40
url: /hu/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) metódus


A Base-64 kódolja az elemeket a megadott bájttömbben, és visszaadja a kódolt adatot karakterláncként.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | A kódolandó bájtok tömbje |
| insert_line_breaks | **bool** | Meghatározza, hogy a kimeneti karakterláncba minden 76 Base-64 karakter után sorvége karaktereket kell-e beszúrni |

### Visszatérési érték

A bemeneti tömb Base-64 kódolt ábrázolását tartalmazó karakterlánc

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) metódus


A Base-64 kódolja egy tartományban lévő elemeket a megadott bájttömbben, és visszaadja a kódolt adatot karakterláncként.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | A kódolandó elemek tartományát tartalmazó bájttömb |
| offset_in | int | Az index az input tömbben, ahol a kódolandó tartomány kezdődik |
| length | int | A kódolandó elemtartomány hossza |
| insert_line_breaks | **bool** | Meghatározza, hogy a kimeneti karakterláncba minden 76 Base-64 karakter után sorvége karaktereket kell-e beszúrni |

### Visszatérési érték

A bemeneti tömb elemtartományának Base-64 kódolt ábrázolását tartalmazó karakterlánc

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) metódus


A Base-64 kódolja az elemeket a megadott bájttömbben, és visszaadja a kódolt adatot karakterláncként.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | A kódolandó bájtok tömbje |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Meghatározza a Base-64 kódolt adat formázási beállításait |

### Visszatérési érték

A bemeneti tömb Base-64 kódolt ábrázolását tartalmazó karakterlánc

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) metódus


A Base-64 kódolja egy tartományban lévő elemeket a megadott bájttömbben, és visszaadja a kódolt adatot karakterláncként.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | A kódolandó elemek tartományát tartalmazó bájttömb |
| offset_in | int | Az index az input tömbben, ahol a kódolandó tartomány kezdődik |
| length | int | A kódolandó elemtartomány hossza |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Meghatározza a Base-64 kódolt adat formázási beállításait |

### Visszatérési érték

A bemeneti tömb elemtartományának Base-64 kódolt ábrázolását tartalmazó karakterlánc

## Lásd még

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)