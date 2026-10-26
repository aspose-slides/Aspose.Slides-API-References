---
title: HandleRepeatedSpaces
second_title: Aspose.Slides Java API Referansı
description: Markdown dışa aktarımı sırasında tekrar eden normal boşluk karakterlerinin nasıl işleneceğini belirtir.
type: docs
url: /tr/com.aspose.slides/handlerepeatedspaces/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Tekrarlanan normal boşluk karakterlerinin Markdown dışa aktarımı sırasında nasıl işleneceğini belirtir.
## Alanlar

| Field | Açıklama |
| --- | --- |
| [None](#None) | Tüm boşluklar, herhangi bir değişiklik yapılmadan normal boşluk karakteri olarak korunur. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | İki veya daha fazla ardışık normal boşluk dizilerini, normal boşluk karakterleri ile kesintisiz boşluk varlıkları (NBSP) arasında değiştirerek dönüştürür. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | İki veya daha fazla ardışık normal boşluk dizilerini, ilk boşluğu normal bir boşluk karakteri olarak koruyup, sonraki tüm boşlukları kesintisiz boşluk varlıkları (NBSP) ile değiştirerek dönüştürür. |
### None {#None}
```
public static final int None
```


Tüm boşluklar, normal boşluk karakteri olarak hiçbir değişiklik yapılmadan korunur. Herhangi bir dönüşüm uygulanmaz ve birden fazla ardışık boşluk olduğu gibi dışa aktarılır.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```


İki veya daha fazla ardışık normal boşluk dizilerini, normal boşluk karakterleri ile kesintisiz boşluk varlıkları (NBSP) arasında değiştirerek dönüştürür. İlk boşluk her zaman normal bir boşluk olarak korunur.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```


İki veya daha fazla ardışık normal boşluk dizilerini, ilk boşluğu normal bir boşluk karakteri olarak koruyup, sonraki tüm boşlukları kesintisiz boşluk varlıkları (NBSP) ile değiştirerek dönüştürür.