---
title: BeginRead()
second_title: Aspose.Slides for C++ API Referencia
description: Elindít egy aszinkron olvasási műveletet.
type: docs
weight: 417
url: /hu/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method

Egy aszinkron olvasási műveletet indít el.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az a bájt tömb, amelyből az adatot olvasni kell. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| count | **int32_t** | A beolvasandó bájtok száma. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amelyet a művelet befejezésekor hívnak meg. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | A felhasználó által biztosított adat, amely egyedileg azonosítja az egyes aszinkron olvasási műveleteket. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a kezdeményezett aszinkron olvasási műveletet képviseli.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Object](../../../system/object/)
* Osztály [SslStream](../)
* Névterület [System::Net::Security](../../)
* Könyvtár [Aspose.Slides](../../../)