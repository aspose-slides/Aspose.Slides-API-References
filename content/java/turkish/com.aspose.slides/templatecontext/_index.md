---
title: TemplateContext
second_title: Aspose.Slides for Java API Referansı
description: Şablon motoru için bir model nesnesi arabirimini temsil eder.
type: docs
url: /tr/com.aspose.slides/templatecontext/
---
**Kalıtım:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Şablon motoru için bir model nesnesi arabirimini temsil eder.
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Bir alt şablon bağlamı oluşturur. |
| [getObject()](#getObject--) | Model nesnesini döndürür. |
| [getOutput()](#getOutput--) | Ana belgenin çıktı öğelerinin koleksiyonunu döndürür. |
| [getLocal()](#getLocal--) | Geçerli şablon bağlamının yerel depolamasını döndürür. |
| [getGlobal()](#getGlobal--) | Ana belgenin global depolamasını döndürür. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


Bir alt şablon bağlamı oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| subModel | TSubModel | Alt model nesnesi. |

**Döndürür:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Verilen model ve ebeveynin çıktı koleksiyonu ve global depolamasıyla yeni şablon bağlamı.
### getObject() {#getObject--}
```
public final TObject getObject()
```


Model nesnesini döndürür. Yalnızca okunabilir Nesne.

**Döndürür:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Ana belgenin çıktı öğelerinin koleksiyonunu döndürür. Yalnızca okunabilir [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Döndürür:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


Geçerli şablon bağlamının yerel depolamasını döndürür. Yalnızca okunabilir [Storage](../../com.aspose.slides/storage).

**Döndürür:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Ana belgenin global depolamasını döndürür. Yalnızca okunabilir [Storage](../../com.aspose.slides/storage).

**Döndürür:**
[Storage](../../com.aspose.slides/storage)