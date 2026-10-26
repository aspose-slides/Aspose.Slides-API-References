---
title: ITemplateEngine
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili mesin template yang mengubah pasangan template dan data menjadi output yang dihasilkan, biasanya HTML.
type: docs
url: /id/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Mewakili mesin template yang mengubah pasangan template dan data menjadi output yang dihasilkan (biasanya HTML).

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Menambahkan template ke dalam koleksi template. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Mengubah template dengan kunci dan objek model yang diberikan menjadi output. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

Menambahkan template ke dalam koleksi template.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | java.lang.String | Kunci untuk template dalam koleksi template. |
| template | java.lang.String | Konten template. |
| modelType | com.aspose.ms.System.Type | Tipe objek model untuk template. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Mengubah template dengan kunci dan objek model yang diberikan menjadi output.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | java.lang.String | Kunci untuk template dalam koleksi template. |
| model | java.lang.Object | Objek model dengan data untuk transformasi. |

**Mengembalikan:**
java.lang.String - Output yang dihasilkan sebagai String.