---
title: IMasterNotesSlideHeaderFooterManager
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: Ana not slaytı alt bilgi, tarih-saat, sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

Ana not slaytı alt bilgi, tarih-saat ve sayfa numarası yer tutucularının ve tüm alt yer tutucularının davranışını tutan yöneticiyi temsil eder. Alt yer tutucular, bağımlı not slaytlarında bulunan yer tutucular anlamına gelir. Bağımlı not slaytları, ana not slaytını kullanır ve ona bağımlıdır.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Ana not slaytı başlık yer tutucusunun ve tüm alt başlık yer tutucularının görünürlüğünü değiştirir. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Ana not slaytı başlık yer tutucusuna ve tüm alt başlık yer tutucularına metin ayarlar. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Ana not slaytı alt bilgi yer tutucusunun ve tüm alt alt bilgi yer tutucularının görünürlüğünü değiştirir. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Ana not slaytı sayfa numarası yer tutucusunun ve tüm alt sayfa numarası yer tutucularının görünürlüğünü değiştirir. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Ana not slaytı tarih-saat yer tutucusunun ve tüm alt tarih-saat yer tutucularının görünürlüğünü değiştirir. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ana not slaytı alt bilgi yer tutucusuna ve tüm alt alt bilgi yer tutucularına metin ayarlar. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ana not slaytı tarih-saat yer tutucusuna ve tüm alt tarih-saat yer tutucularına metin ayarlar. |

### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

Ana not slaytı başlık yer tutucusunun ve tüm alt başlık yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı not slaytlarında bulunan yer tutucular anlamına gelir. Bağımlı not slaytları, ana not slaytını kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - başlık yer tutucularını görünür yapar, aksi takdirde gizler. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

Ana not slaytı başlık yer tutucusuna ve tüm alt başlık yer tutucularına metin ayarlar. Alt yer tutucular, bağımlı not slaytlarında bulunan yer tutucular anlamına gelir. Bağımlı not slaytları, ana not slaytını kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Ana not slaytı alt bilgi yer tutucusunun ve tüm alt alt bilgi yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı not slaytlarında bulunan yer tutucular anlamına gelir. Bağımlı not slaytları, ana not slaytını kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - alt bilgi yer tutucularını görünür yapar, aksi takdirde gizler. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Ana not slaytı sayfa numarası yer tutucusunun ve tüm alt sayfa numarası yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı not slaytlarında bulunan yer tutucular anlamına gelir. Bağımlı not slaytları, ana not slaytını kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - sayfa numarası yer tutucularını görünür yapar, aksi takdirde gizler. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Ana not slaytı tarih-saat yer tutucusunun ve tüm alt tarih-saat yer tutucularının görünürlüğünü değiştirir. Alt yer tutucular, bağımlı not slaytlarında bulunan yer tutucular anlamına gelir. Bağımlı not slaytları, ana not slaytını kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | true - tarih-saat yer tutucularını görünür yapar, aksi takdirde gizler. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Ana not slaytı alt bilgi yer tutucusuna ve tüm alt alt bilgi yer tutucularına metin ayarlar. Alt yer tutucular, bağımlı not slaytlarında bulunan yer tutucular anlamına gelir. Bağımlı not slaytları, ana not slaytını kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Ana not slaytı tarih-saat yer tutucusuna ve tüm alt tarih-saat yer tutucularına metin ayarlar. Alt yer tutucular, bağımlı not slaytlarında bulunan yer tutucular anlamına gelir. Bağımlı not slaytları, ana not slaytını kullanır ve ona bağımlıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Ayarlanacak metin. |