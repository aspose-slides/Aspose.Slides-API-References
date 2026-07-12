---
title: IGradientStopCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: 勾配ストップのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/igradientstopcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

勾配ストップのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | インデックスで勾配ストップを取得します。 |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | 新しい勾配ストップを作成し、コレクションの末尾に追加します。 |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | 新しい勾配ストップを作成し、コレクションの末尾に追加します。 |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | 新しい勾配ストップを作成し、コレクションの末尾に追加します。 |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | 新しい勾配ストップを作成し、指定したインデックスに挿入します。 |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | 新しい勾配ストップを作成し、指定したインデックスに挿入します。 |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | 新しい勾配ストップを作成し、指定したインデックスに挿入します。 |
| [removeAt(int index)](#removeAt-int-) | 指定したインデックスの勾配ストップを削除します。 |
| [clear()](#clear--) | コレクションからすべての勾配ストップを削除します。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

インデックスで勾配ストップを取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IGradientStop](../../com.aspose.slides/igradientstop)

### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```

新しい勾配ストップを作成し、コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | float | 新しい勾配ストップの位置。 |
| color | java.lang.Integer | 新しい勾配ストップの色。 |

**戻り値:**
[IGradientStop](../../com.aspose.slides/igradientstop) - コレクション内の新しい勾配ストップのインデックス。

### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

新しい勾配ストップを作成し、コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | float | 新しい勾配ストップの位置。 |
| presetColor | int | 新しい勾配ストップの色。 |

**戻り値:**
[IGradientStop](../../com.aspose.slides/igradientstop) - コレクション内の新しい勾配ストップのインデックス。

### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

新しい勾配ストップを作成し、コレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | float | 新しい勾配ストップの位置。 |
| schemeColor | int | 新しい勾配ストップの色。 |

**戻り値:**
[IGradientStop](../../com.aspose.slides/igradientstop) - コレクション内の新しい勾配ストップのインデックス。

### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```

新しい勾配ストップを作成し、指定したインデックスに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しい勾配ストップを挿入するコレクション内のインデックス。 |
| position | float | 新しい勾配ストップの位置。 |
| color | java.lang.Integer | 新しい勾配ストップの色。 |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

新しい勾配ストップを作成し、指定したインデックスに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しい勾配ストップを挿入するコレクション内のインデックス。 |
| position | float | 新しい勾配ストップの位置。 |
| presetColor | int | 新しい勾配ストップの色。 |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

新しい勾配ストップを作成し、指定したインデックスに挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しい勾配ストップを挿入するコレクション内のインデックス。 |
| position | float | 新しい勾配ストップの位置。 |
| schemeColor | int | 新しい勾配ストップの色。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定したインデックスの勾配ストップを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除すべき勾配ストップのインデックス。 |

### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべての勾配ストップを削除します。