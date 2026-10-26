---
title: ITemplateEngine
second_title: Aspose.Slides for Java API Reference
description: Mewakili mesin templat yang mengubah pasangan templat dan data menjadi output yang dihasilkan biasanya HTML.
type: docs
url: /id/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Mewakili mesin templat yang mengubah pasangan templat dan data menjadi output yang dihasilkan (biasanya HTML).

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Menambahkan templat ke koleksi templat. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Mengubah templat dengan kunci yang diberikan dan objek model menjadi output. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

Menambahkan templat ke koleksi templat.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | java.lang.String | Kunci untuk templat dalam koleksi templat. |
| template | java.lang.String | Konten templat. |
| modelType | com.aspose.ms.System.Type | Tipe objek model untuk templat. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Mengubah templat dengan kunci yang diberikan dan objek model menjadi output.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | java.lang.String | Kunci untuk templat dalam koleksi templat. |
| model | java.lang.Object | Objek model dengan data untuk transformasi. |

**Mengembalikan:**
java.lang.String - Output yang dihasilkan sebagai String.