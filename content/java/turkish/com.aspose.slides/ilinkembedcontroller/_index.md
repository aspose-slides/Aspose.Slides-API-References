---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
url: /tr/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Kaydetme sırasında nesnenin nasıl işleneceğini belirlemek için kullanılan geri çağırma arabirimi.

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Nesnenin nerede saklanması gerektiğini belirler. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Harici bir nesne için bir URL döndürür. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Harici nesneyi kaydeder. |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

Nesnenin nerede saklanması gerektiğini belirler. Bu yöntem, her nesne id için bir kez çağrılır. Aynı veri, semanticName ve contentType'a sahip ancak farklı id'ye sahip iki nesnenin olmayacağı garantilenmez.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | int | Nesne id. Bu id, kaydetme işlemi boyunca benzersizdir. |
| entityData | byte[] | Nesne ikili verisi. Bu parametre null olabilir, nesne ikili verisi henüz oluşturulmamışsa. |
| semanticName | java.lang.String | Nesnenin anlamını tanımlayan kısa bir metin. Controller bunu harici nesne adının bir parçası olarak kullanabilir, ancak adların benzersiz olmasını ve yalnızca izin verilen karakterleri içermesini sağlamak dispatcher'ın sorumluluğundadır. |
| contentType | java.lang.String | Nesnenin MIME türü. |
| recomendedExtension | java.lang.String | Bu MIME türü için önerilen dosya adı uzantısı. |

**Döndürür:**  
int - Karar

### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```

Harici bir nesne için bir URL döndürür. Bu yöntem, \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) döndürdüğünde her zaman çağrılır ve \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) döndürdüğünde ancak gömme mümkün olmadığında çağrılabilir. Aynı nesne id için birden fazla kez çağrılabilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | int | Nesne id. Bu id, kaydetme işlemi boyunca benzersizdir. |
| referrer | int | Referans veren nesnenin id’si veya kök belge tarafından referans alındığında 0. Göreli bağlantı oluşturmak için kullanılabilir. |

**Döndürür:**  
java.lang.String - Harici nesnenin URL'si veya bu nesne yok sayılmalıysa null.

### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```

Harici nesneyi kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | int | Nesne id. Bu id, kaydetme işlemi boyunca benzersizdir. |
| entityData | byte[] | Nesne ikili verisi. Bu parametre null olamaz. |