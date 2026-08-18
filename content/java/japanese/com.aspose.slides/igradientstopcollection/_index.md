---
title: IGradientStopCollection
second_title: Aspose.Slides for Java API リファレンス
description: グラデーション ストップのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/igradientstopcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

グラデーション ストップのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | インデックスでグラデーション ストップを返します。 |
| [add(float position, Color color)](#add-float-java.awt.Color-) | 新しいグラデーション ストップを作成し、コレクションの末尾に追加します。 |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | 新しいグラデーション ストップを作成し、コレクションの末尾に追加します。 |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | 新しいグラデーション ストップを作成し、コレクションの末尾に追加します。 |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | 新しいグラデーション ストップを作成し、指定されたインデックスにコレクションへ挿入します。 |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | 新しいグラデーション ストップを作成し、指定されたインデックスにコレクションへ挿入します。 |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | 新しいグラデーション ストップを作成し、指定されたインデックスにコレクションへ挿入します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのグラデーション ストップを削除します。 |
| [clear()](#clear--) | コレクションからすべてのグラデーション ストップを削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

インデックスでグラデーション ストップを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```

新しいグラデーション ストップを作成し、コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | float | 新しいグラデーション ストップの位置。 |
| color | java.awt.Color | 新しいグラデーション ストップの色。 |

**戻り値:**
[IGradientStop](../../com.aspose.slides/igradientstop) - コレクション内の新しいグラデーション ストップのインデックス。
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

新しいグラデーション ストップを作成し、コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | float | 新しいグラデーション ストップの位置。 |
| presetColor | int | 新しいグラデーション ストップの色。 |

**戻り値:**
[IGradientStop](../../com.aspose.slides/igradientstop) - コレクション内の新しいグラデーション ストップのインデックス。
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

新しいグラデーション ストップを作成し、コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | float | 新しいグラデーション ストップの位置。 |
| schemeColor | int | 新しいグラデーション ストップの色。 |

**戻り値:**
[IGradientStop](../../com.aspose.slides/igradientstop) - コレクション内の新しいグラデーション ストップのインデックス。
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```

新しいグラデーション ストップを作成し、指定されたインデックスにコレクションへ挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいグラデーション ストップが挿入されるコレクション内のインデックス。 |
| position | float | 新しいグラデーション ストップの位置。 |
| color | java.awt.Color | 新しいグラデーション ストップの色。 |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

新しいグラデーション ストップを作成し、指定されたインデックスにコレクションへ挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいグラデーション ストップが挿入されるコレクション内のインデックス。 |
| position | float | 新しいグラデーション ストップの位置。 |
| presetColor | int | 新しいグラデーション ストップの色。 |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

新しいグラデーション ストップを作成し、指定されたインデックスにコレクションへ挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいグラデーション ストップが挿入されるコレクション内のインデックス。 |
| position | float | 新しいグラデーション ストップの位置。 |
| schemeColor | int | 新しいグラデーション ストップの色。 |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定されたインデックスのグラデーション ストップを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除すべきグラデーション ストップのインデックス。 |
### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべてのグラデーション ストップを削除します。