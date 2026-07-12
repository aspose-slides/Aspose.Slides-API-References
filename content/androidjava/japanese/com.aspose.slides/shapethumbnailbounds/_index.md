---
title: ShapeThumbnailBounds
second_title: Java API リファレンスによる Aspose.Slides for Android
description: シェイプサムネイル境界の種類の列挙です。
type: docs
url: /ja/com.aspose.slides/shapethumbnailbounds/
---
**継承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

シェイプサムネイル境界の種類の列挙です。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Slide](#Slide) | シェイプサムネイルはスライドサイズと同じサイズになります。 |
| [Shape](#Shape) | シェイプサムネイルはシェイプのアウトライン設定を考慮したシェイプ境界矩形と同じサイズになります。 |
| [Appearance](#Appearance) | シェイプサムネイルはシェイプの外観（スライドの境界内）と同じサイズになります。 |
### Slide {#Slide}
```
public static final int Slide
```

シェイプサムネイルはスライドサイズと同じサイズになります。シェイプの位置は保存されます。

### Shape {#Shape}
```
public static final int Shape
```

シェイプサムネイルはシェイプのアウトライン設定を考慮したシェイプ境界矩形と同じサイズになります。

### Appearance {#Appearance}
```
public static final int Appearance
```

シェイプサムネイルはシェイプの外観（スライドの境界内）と同じサイズになります。シェイプの外観がシェイプ境界に収まらない場合があります。例として、回転、鋭角の斜接結合、3D 効果などがあります。