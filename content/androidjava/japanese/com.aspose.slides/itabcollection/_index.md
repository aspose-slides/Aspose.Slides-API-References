---
title: ITabCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: タブのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/itabcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

タブのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [add(double position, int align)](#add-double-int-) | コレクションに Tab を追加します。 |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | コレクションに Tab を追加します。 |
| [clear()](#clear--) | コレクションからすべての要素を削除します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定されたインデックスの要素を削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

指定されたインデックスの要素を取得します。読み取り専用 [ITab](../../com.aspose.slides/itab)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

コレクションに Tab を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | double | タブの位置。 |
| align | int | タブの配置。 |

**戻り値:**
[ITab](../../com.aspose.slides/itab) - 追加されたタブ。
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

コレクションに Tab を追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | コレクションの末尾に追加される Tab オブジェクト。 |

**戻り値:**
int - タブが追加されたインデックス。
### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべての要素を削除します。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

コレクションの指定されたインデックスの要素を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。 |