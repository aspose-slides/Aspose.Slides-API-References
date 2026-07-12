---
title: HandleRepeatedSpaces
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: Markdown dışa aktarımı sırasında yinelenen normal boşluk karakterlerinin nasıl işleneceğini belirler.
type: docs
url: /tr/com.aspose.slides/handlerepeatedspaces/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Markdown dışa aktarımı sırasında yinelenen normal boşluk karakterlerinin nasıl işleneceğini belirtir.
## Fields

| Alan | Açıklama |
| --- | --- |
| [None](#None) | Tüm boşluklar, normal boşluk karakterleri olarak hiçbir değişiklik yapılmadan korunur. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | İki veya daha fazla ardışık normal boşluk dizilerini, normal boşluk karakterleri ile kırılmayan boşluk varlıkları (NBSP) arasında dönüşümlü olarak dönüştürür. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | İki veya daha fazla ardışık normal boşluk dizilerini, ilk boşluğu normal bir boşluk karakteri olarak koruyup kalan tüm boşlukları kırılmayan boşluk varlıkları (NBSP) ile değiştirerek dönüştürür. |
### None {#None}
```
public static final int None
```


Tüm boşluklar, normal boşluk karakterleri olarak hiçbir değişiklik yapılmadan korunur. Hiçbir dönüşüm uygulanmaz ve birden fazla ardışık boşluk olduğu gibi dışa aktarılır.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```


İki veya daha fazla ardışık normal boşluk dizilerini, normal boşluk karakterleri ile kırılmayan boşluk varlıkları (NBSP) arasında dönüşümlü olarak dönüştürür. İlk boşluk her zaman normal bir boşluk olarak korunur.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```


İki veya daha fazla ardışık normal boşluk dizilerini, ilk boşluğu normal bir boşluk karakteri olarak koruyup kalan tüm boşlukları kırılmayan boşluk varlıkları (NBSP) ile değiştirerek dönüştürür.