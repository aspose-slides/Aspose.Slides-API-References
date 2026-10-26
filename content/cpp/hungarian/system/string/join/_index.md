---
title: Join()
second_title: Aspose.Slides C++ API referencia
description: A tömb elemeit a karakterláncot elválasztóként használva fűzi össze.
type: docs
weight: 846
url: /hu/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) metódus


A tömb elemeit a karakterláncot elválasztóként használva fűzi össze.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) a tömb elemei között, amikor összevonja őket. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) a csatlakoztatandó részekből. |
| startIndex | int | Az első index a tömbben, ahonnan az összefűzést elindítja. |
| count | int | Az összevonandó tömb elemek száma. -1 azt jelenti, hogy 'amíg a tömb vége'. |

### Visszatérési érték

[String](../) a csatlakozott tömb elemeket ábrázolja.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) metódus


A tömb elemeit a karakterláncot elválasztóként használva fűzi össze.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) a tömb elemei között, amikor összevonja őket. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | ArrayView a csatlakoztatandó részekből. |
| startIndex | int | Az első index a tömbben, ahonnan az összefűzést elindítja. |
| count | int | Az összevonandó tömb elemek száma. -1 azt jelenti, hogy 'amíg a tömb vége'. |

### Visszatérési érték

[String](../) a csatlakozott tömb elemeket ábrázolja.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) metódus


A tömb elemeit a karakterláncot elválasztóként használva fűzi össze.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) a tömb elemei között, amikor összevonja őket. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - a részek felsorolható objektuma |

### Visszatérési érték

[String](../) a csatlakozott elemeket ábrázolja.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) metódus


A tömb elemeit a karakterláncot elválasztóként használva fűzi össze.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) a tömb elemei között, amikor összevonja őket. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) a csatlakoztatandó részekből. |

### Visszatérési érték

[String](../) a csatlakozott elemeket ábrázolja.

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../)
* Osztály [IEnumerable](../../../system.collections.generic/ienumerable/)
* Osztály [Object](../../object/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)