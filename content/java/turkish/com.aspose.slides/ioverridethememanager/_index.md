---
title: IOverrideThemeManager
second_title: Aspose.Slides for Java API Referansı
description: Farklı türde geçersiz kılınmış temalara erişim sağlar.
type: docs
url: /tr/com.aspose.slides/ioverridethememanager/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Farklı türde geçersiz kılınmış temalara erişim sağlar.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | OverrideTheme'un, kalıtılmış etkili temayı geçersiz kılıp kılmadığını belirler. |
| [getOverrideTheme()](#getOverrideTheme--) | Geçersiz kılan tema nesnesini döndürür. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Geçersiz kılan tema nesnesini döndürür. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

OverrideTheme'un, kalıtılmış etkili temayı geçersiz kılıp kılmadığını belirler. OverrideTheme'u geçersiz kılma için OverrideTheme.Init\*() metodlarını kullanın. OverrideTheme'un geçersiz kılmasını durdurmak için OverrideTheme.Clear() metodunu kullanın. Salt okunur boolean.

**Döndürür:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

Geçersiz kılan tema nesnesini döndürür. Okunur/yazılır [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Döndürür:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

Geçersiz kılan tema nesnesini döndürür. Okunur/yazılır [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |