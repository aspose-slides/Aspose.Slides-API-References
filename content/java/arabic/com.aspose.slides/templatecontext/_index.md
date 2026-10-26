---
title: TemplateContext
second_title: Aspose.Slides لمرجعية API جافا
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
| [getOutput()](#getOutput--) | يرجع مجموعة من عناصر الإخراج في المستند المضيف. |
| [getLocal()](#getLocal--) | يرجع التخزين المحلي لسياق القالب الحالي. |
| [getGlobal()](#getGlobal--) | يرجع التخزين العام للمستند المضيف. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```

ينشئ سياق قالب فرعي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| subModel | TSubModel | كائن نموذج فرعي. |

**الإرجاع:**
[TemplateContext](../../com.aspose.slides/templatecontext) - سياق قالب جديد بالنموذج المحدد ومجموعة إخراج الأصل والتخزين العام.
### getObject() {#getObject--}
```
public final TObject getObject()
```

يرجع كائن النموذج. كائن للقراءة فقط Object.

**الإرجاع:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```

يرجع مجموعة من عناصر الإخراج في المستند المضيف. للقراءة فقط [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**الإرجاع:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```

يرجع التخزين المحلي لسياق القالب الحالي. للقراءة فقط [Storage](../../com.aspose.slides/storage).

**الإرجاع:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

يرجع التخزين العام للمستند المضيف. للقراءة فقط [Storage](../../com.aspose.slides/storage).

**الإرجاع:**
[Storage](../../com.aspose.slides/storage)