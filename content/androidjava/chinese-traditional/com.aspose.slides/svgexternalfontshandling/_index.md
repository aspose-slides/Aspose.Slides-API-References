---
title: SvgExternalFontsHandling
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示一種處理文字繪製時使用的外部字型的方式。
type: docs
url: /zh-hant/com.aspose.slides/svgexternalfontshandling/
---
**繼承:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SvgExternalFontsHandling extends System.Enum
```

表示一種處理文字繪製時使用的外部字型的方式。
## 欄位

| 欄位 | 說明 |
| --- | --- |
| [AddLinksToFontFiles](#AddLinksToFontFiles) | 將連結至個別字型檔案加入 SVG 檔案的 style 區段。 |
| [Embed](#Embed) | 直接將字型資料儲存至 SVG 檔案。 |
| [Vectorize](#Vectorize) | 將所有使用外部字型的文字儲存為圖形。 |
### AddLinksToFontFiles {#AddLinksToFontFiles}
```
public static final int AddLinksToFontFiles
```

將連結至個別字型檔案加入 SVG 檔案的 style 區段。

### Embed {#Embed}
```
public static final int Embed
```

直接將字型資料儲存至 SVG 檔案。請在使用此選項前檢查所有外部字型的授權合約。

### Vectorize {#Vectorize}
```
public static final int Vectorize
```

將所有使用外部字型的文字儲存為圖形。