---
title: InvokeCompletedEventArgs()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir örnek oluşturur.
type: docs
weight: 14
url: /tr/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) yapıcı


Yeni bir örnek oluşturur.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | Asenkron bir işlem sırasında oluşan herhangi bir hata. |
| cancelled | **bool** | Asenkron bir işlemin iptal edilip edilmediğini belirten bir değer. |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) yöntemine geçirilen isteğe bağlı kullanıcı tarafından sağlanan durum nesnesi. |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Asenkron işlem sonuçlarının bir koleksiyonu. |

## İlgili

* Tip Tanımı [Exception](../../../system/exception/)
* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [InvokeCompletedEventArgs](../)
* Ad Alanı [System::Web::Services::Protocols](../../)
* Kütüphane [Aspose.Slides](../../../)