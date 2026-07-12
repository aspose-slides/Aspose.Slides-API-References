---
title: ILinkEmbedController
second_title: Aspose.Slides for Android via Java API Reference
description: Kaydetme sırasında nesnenin nasıl işleneceğini belirlemek için kullanılan geri arama arayüzü.
type: docs
url: /tr/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Kaydetme sırasında nesnenin nasıl işleneceğini belirlemek için kullanılan geri arama arayüzü.
## Yöntemler

| Metod | Açıklama |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Nesnenin nerede depolanması gerektiğini belirler. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Harici bir nesne için bir URL döndürür. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Harici nesneyi kaydeder. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

Nesnenin nerede depolanması gerektiğini belirler. Bu yöntem her nesne kimliği için bir kez çağrılır. Aynı veri, semanticName ve contentType değerlerine sahip ancak farklı kimliğe sahip iki nesnenin olmayacağı garanti edilmez.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | int | Nesne kimliği. Bu kimlik kaydetme işlemi boyunca benzersizdir. |
| entityData | byte[] | Nesnenin ikili verisi. Bu parametre null olabilir, eğer nesnenin ikili verisi henüz üretilmemişse. |
| semanticName | java.lang.String | Nesnenin anlamını tanımlayan kısa bir metin. Denetleyici bunu harici nesne adının bir parçası olarak kullanabilir, ancak adların benzersiz olmasını ve yalnızca izin verilen karakterleri içermesini sağlamak dağıtıcıya bırakılmıştır. |
| contentType | java.lang.String | Nesnenin MIME türü. |
| recomendedExtension | java.lang.String | Bu MIME türü için önerilen dosya uzantısı. |

**Dönüş Değeri:**
int - Karar
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```

Harici bir nesne için bir URL döndürür. Bu yöntem, \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) döndürdüğünde her zaman çağrılır ve \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) döndürdüğünde ancak gömme mümkün olmadığında çağrılabilir. Aynı nesne kimliği için birden fazla kez çağrılabilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | int | Nesne kimliği. Bu kimlik kaydetme işlemi boyunca benzersizdir. |
| referrer | int | Referans veren nesnenin kimliği ya da kök belge tarafından referans alındığında 0. Göreli bağlantı oluşturmak için kullanılabilir. |

**Dönüş Değeri:**
java.lang.String - Harici nesnenin URL'si veya bu nesne yok sayılmalıysa null.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```

Harici nesneyi kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | int | Nesne kimliği. Bu kimlik kaydetme işlemi boyunca benzersizdir. |
| entityData | byte[] | Nesnenin ikili verisi. Bu parametre null olamaz. |