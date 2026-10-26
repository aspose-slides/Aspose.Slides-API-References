---
title: IColorOperationCollection
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: 色変換操作のコレクションを表します。
type: docs
url: /ja/com.aspose.slides/icoloroperationcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

色変換操作のコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの操作を取得または設定します。 |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | 指定されたインデックスの操作を取得または設定します。 |
| [add(int operation, float parameter)](#add-int-float-) | コレクションの末尾に新しい操作を追加します。 |
| [add(int operation)](#add-int-) | コレクションの末尾に新しい操作を追加します。 |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | コレクションに新しい操作を挿入します。 |
| [insert(int position, int operation)](#insert-int-int-) | コレクションに新しい操作を挿入します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションから色操作を削除します。 |
| [clear()](#clear--) | すべての色操作を削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

指定されたインデックスの操作を取得または設定します。読み取り/書き込み [IColorOperation](../../com.aspose.slides/icoloroperation)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

指定されたインデックスの操作を取得または設定します。読み取り/書き込み [IColorOperation](../../com.aspose.slides/icoloroperation)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

コレクションの末尾に新しい操作を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| operation | int | 操作のタイプ。 |
| parameter | float | 操作のパラメータ。 |

**戻り値:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 追加された操作。
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

コレクションの末尾に新しい操作を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| operation | int | 操作のタイプ。 |

**戻り値:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 追加された操作。
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

コレクションに新しい操作を挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | int | 操作が挿入されるインデックス。 |
| operation | int | 操作のタイプ。 |
| parameter | float | 操作のパラメータ。 |

**戻り値:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 挿入された操作。
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

コレクションに新しい操作を挿入します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | int | 操作が挿入されるインデックス。 |
| operation | int | 操作のタイプ。 |

**戻り値:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 挿入された操作。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

コレクションから色操作を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する色操作のインデックス。 |

### clear() {#clear--}
```
public abstract void clear()
```

すべての色操作を削除します。