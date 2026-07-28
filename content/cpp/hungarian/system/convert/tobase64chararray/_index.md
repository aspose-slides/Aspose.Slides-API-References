---
title: ToBase64CharArray()
second_title: Aspose.Slides C++ API referenciája
description: Base-64 kódolja a megadott bájt tömbben lévő elemtartományt, és a kódolt adatot Unicode karakterek tömbjeként tárolja.
type: docs
weight: 27
url: /hu/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) method

A Base-64 kódolja a megadott bájt tömbben lévő elemtartományt, és a kódolt adatot Unicode karakterek tömbjeként tárolja.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | A bájtok tömbje, amely a kódolandó elemtartományt tartalmazza |
| offset_in | int | Az bemeneti tömbben egy elem indexe, ahol a kódolandó tartomány kezdődik |
| length | int | A kódolandó elemtartomány hossza |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Az kimeneti tömbre mutató állandó referencia, amelybe az eredmény adat kerül |
| offset_out | int | Az kimeneti tömb egy indexe, ahol az eredmény adat elhelyezése kezdődik |
| insert_line_breaks | **bool** | Meghatározza, hogy a sor megtörés karaktereket kell-e beszúrni a kimeneti tömbbe minden 76 base-64 karakter után |

### Visszatérési érték

A kimeneti tömbbe írt karakterek száma

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) method

A Base-64 kódolja a megadott bájt tömbben lévő elemtartományt, és a kódolt adatot Unicode karakterek tömbjeként tárolja.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | A bájtok tömbje, amely a kódolandó elemtartományt tartalmazza |
| offset_in | int | Az bemeneti tömbben egy elem indexe, ahol a kódolandó tartomány kezdődik |
| length | int | A kódolandó elemtartomány hossza |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Az kimeneti tömbre mutató állandó referencia, amelybe az eredmény adat kerül |
| offset_out | int | Az kimeneti tömb egy indexe, ahol az eredmény adat elhelyezése kezdődik |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Formázási beállításokat határoz meg a base-64 kódolt adatokhoz |

### Visszatérési érték

A kimeneti tömbbe írt karakterek száma

## Lásd még

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)