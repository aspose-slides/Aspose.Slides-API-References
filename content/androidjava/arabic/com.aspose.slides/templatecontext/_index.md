---
title: TemplateContext
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل واجهة كائن نموذج لمحرك القوالب.
type: docs
url: /ar/com.aspose.slides/templatecontext/
---
**الوراثة:**  
java.lang.Object
```
public final class TemplateContext<TObject>
```

يمثل واجهة كائن نموذج لمحرك القوالب.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | ينشئ سياق قالب فرعي. |
| [getObject()](#getObject--) | يرجع كائن النموذج. |
| [getOutput()](#getOutput--) | يرجع مجموعة عناصر الإخراج للمستند المستضيف. |
| [getLocal()](#getLocal--) | يرجع التخزين المحلي لسياق القالب الحالي. |
| [getGlobal()](#getGlobal--) | يرجع التخزين العالمي للمستند المستضيف. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


ينشئ سياق قالب فرعي.

**المعلمات:**
| المعلم | النوع | الوصف |
| --- | --- | --- |
| subModel | TSubModel | كائن نموذج فرعي. |

**القيمة المرجعة:**
[TemplateContext](../../com.aspose.slides/templatecontext) - سياق قالب جديد مع النموذج المعطى ومجموعة إخراج الوالد والتخزين العالمي.

### getObject() {#getObject--}
```
public final TObject getObject()
```


يرجع كائن النموذج. Object للقراءة فقط.

**القيمة المرجعة:**
TObject

### getOutput() {#getOutput--}
```
public final Output getOutput()
```


يرجع مجموعة عناصر الإخراج للمستند المستضيف. للقراءة فقط [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**القيمة المرجعة:**
[Output](../../com.aspose.slides/output)

### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


يرجع التخزين المحلي لسياق القالب الحالي. للقراءة فقط [Storage](../../com.aspose.slides/storage).

**القيمة المرجعة:**
[Storage](../../com.aspose.slides/storage)

### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


يرجع التخزين العالمي للمستند المستضيف. للقراءة فقط [Storage](../../com.aspose.slides/storage).

**القيمة المرجعة:**
[Storage](../../com.aspose.slides/storage)