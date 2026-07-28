---
title: ToSingle()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a megadott tömb négy bájtját a megadott indexnél kezdve egyszeres pontosságú lebegőpontos értékké.
type: docs
weight: 131
url: /hu/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) metódus


Átalakítja a megadott tömb négy bájtját, a megadott indexnél kezdve, egyszeres pontosságú lebegőpontos értékké.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) amely tartalmazza az átalakítandó bájtokat |
| startIndex | int | [Index](../../index/) a tömbben, ahol a bájtok átalakítását kell elkezdeni |

### Visszatérési érték

Az átalakítás eredményeként kapott egyszeres pontosságú lebegőpontos érték

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) metódus


Átalakítja a megadott tömb négy bájtját, a megadott indexnél kezdve, egyszeres pontosságú lebegőpontos értékké.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView amely tartalmazza az átalakítandó bájtokat |
| startIndex | int | [Index](../../index/) a tömbben, ahol a bájtok átalakítását kell elkezdeni |

### Visszatérési érték

Az átalakítás eredményeként kapott egyszeres pontosságú lebegőpontos érték

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [BitConverter](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)