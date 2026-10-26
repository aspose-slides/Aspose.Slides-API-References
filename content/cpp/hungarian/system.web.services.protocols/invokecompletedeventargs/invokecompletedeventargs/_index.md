---
title: InvokeCompletedEventArgs()
second_title: Aspose.Slides C++ API hivatkozás
description: Új példányt hoz létre.
type: docs
weight: 14
url: /hu/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) constructor

Új példányt hoz létre.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | Bármilyen hiba, amely egy aszinkron művelet során történt. |
| cancelled | **bool** | Egy érték, amely jelzi, hogy egy aszinkron művelet leállt-e. |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Az opcionális felhasználó által megadott állapotobjektum, amely a [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) metódusnak kerül átadásra. |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Az aszinkron művelet eredményeinek gyűjteménye. |

## Lásd még

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [Object](../../../system/object/)
* Osztály [InvokeCompletedEventArgs](../)
* Névtér [System::Web::Services::Protocols](../../)
* Könyvtár [Aspose.Slides](../../../)