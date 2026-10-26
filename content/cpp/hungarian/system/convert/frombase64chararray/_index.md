---
title: FromBase64CharArray()
second_title: Aspose.Slides C++ API-referencia
description: Dekódolja a base-64 kódolású adatokat, amelyeket a Unicode karakterek tömbjében lévő tartományként ábrázolnak.
type: docs
weight: 53
url: /hu/system/convert/frombase64chararray/
---
## Convert::FromBase64CharArray(const ArrayPtr\<char_t\>\&, int, int) metódus


Dekódolja a base-64 kódolású adatokat, amelyeket a Unicode karakterek tömbjében lévő tartományként ábrázolnak.

```cpp
static ArrayPtr<uint8_t> System::Convert::FromBase64CharArray(const ArrayPtr<char_t> &in_array, int offset, int length)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | A tömb, amely a dekódolandó adatot tartalmazza |
| offset | int | A bemeneti tömb azon pozíciója, ahol a dekódolandó tartomány kezdődik |
| length | int | A dekódolandó tartomány hossza |

### Visszatérési érték

Egy bájt tömb, amely a dekódolt adatot tartalmazza

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Struktúra [Convert](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)