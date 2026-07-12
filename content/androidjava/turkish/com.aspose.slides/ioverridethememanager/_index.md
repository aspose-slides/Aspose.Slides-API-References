---
title: IOverrideThemeManager
second_title: Aspose.Slides for Android için Java API Referansı
description: Geçersiz kılınmış temaların farklı türlerine erişim sağlar.
type: docs
url: /tr/com.aspose.slides/ioverridethememanager/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Geçersiz kılınmış temaların farklı türlerine erişim sağlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | OverrideTheme, kalıtılan etkili temayı geçersiz kılıp kılmadığını belirler. |
| [getOverrideTheme()](#getOverrideTheme--) | Geçersiz kılınan tema nesnesini döndürür. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Geçersiz kılınan tema nesnesini döndürür. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

OverrideTheme, kalıtılan etkili temayı geçersiz kılıp kılmadığını belirler. OverrideTheme'i geçersiz kılma için OverrideTheme.Init\*() yöntemlerini kullanın. OverrideTheme'in geçersiz kılmasını devre dışı bırakmak için OverrideTheme.Clear() yöntemini kullanın. Salt okunur boolean.

**Döndürür:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

Geçersiz kılınan tema nesnesini döndürür. Okuma/yazma [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Döndürür:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

Geçersiz kılınan tema nesnesini döndürür. Okuma/yazma [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |