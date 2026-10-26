---
title: IXamlOutputSaver
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an output saver implementation for transfer data to the external storage.
type: docs
url: /ar/com.aspose.slides/ixamloutputsaver/
---```
public interface IXamlOutputSaver
```

يمثل تنفيذًا لحفظ المخرجات لنقل البيانات إلى التخزين الخارجي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [save(String path, byte[] data)](#save-java.lang.String-byte---) | يحفظ مصفوفة من البايتات إلى موقع الوجهة. |
### save(String path, byte[] data) {#save-java.lang.String-byte---}
```
public abstract void save(String path, byte[] data)
```

يحفظ مصفوفة من البايتات إلى موقع الوجهة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | java.lang.String | مسار الوجهة. |
| data | byte[] | بيانات ثنائية لحفظها إلى موقع الوجهة. |