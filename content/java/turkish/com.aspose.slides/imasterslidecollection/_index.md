---
title: IMasterSlideCollection
second_title: Aspose.Slides için Java API Referansı
description: Ana slaytların bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/imasterslidecollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Bir ana slayt koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Koleksiyondan belirli bir nesnenin ilk örneğini kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyondaki belirtilen indeksteki öğeyi kaldırır. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Kullanılmayan ana slaytları kaldırır. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Belirtilen bir ana slaytın bir kopyasını koleksiyonun sonuna ekler. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Belirtilen bir ana slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

Belirtilen indeksteki öğeyi alır. Yalnızca okunur [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş Değeri:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

Koleksiyondan belirli bir nesnenin ilk örneğini kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Kaldırılacak ana slayt. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Koleksiyondaki belirtilen indeksteki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

Kullanılmayan ana slaytları kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ignorePreserveField | boolean | Bu yöntemin, [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) özelliği true olarak ayarlanmış olsa bile kullanılmayan ana slaytı kaldırıp kaldırmayacağını belirler. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

Belirtilen bir ana slaytın bir kopyasını koleksiyonun sonuna ekler. Bağlantılı yerleşim slaytları da kopyalanacaktır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Klonlanacak slayt. |

**Dönüş Değeri:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Eklenen slayt.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Belirtilen bir ana slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler. Bağlantılı yerleşim slaytları da kopyalanacaktır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaydın indeksi. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Klonlanacak slayt. |

**Dönüş Değeri:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Eklen ana slayt.