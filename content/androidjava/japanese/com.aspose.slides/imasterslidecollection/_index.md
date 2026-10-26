---
title: IMasterSlideCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: マスタースライドのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/imasterslidecollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

マスタースライドのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションの指定されたインデックスの要素を削除します。 |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | 未使用のマスタースライドを削除します。 |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | 指定されたマスタースライドのコピーをコレクションの末尾に追加します。 |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | 指定されたマスタースライドのコピーをコレクションの指定位置に挿入します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

指定されたインデックスの要素を取得します。読み取り専用 [IMasterSlide](../../com.aspose.slides/imasterslide)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

コレクションから特定のオブジェクトの最初の出現を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | コレクションから削除するマスタースライド。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

コレクションの指定されたインデックスの要素を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する要素のゼロベースインデックス。 |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

未使用のマスタースライドを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ignorePreserveField | boolean | このメソッドが、[IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) プロパティが true に設定されていても未使用のマスターを削除すべきかどうかを決定します。 |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

指定されたマスタースライドのコピーをコレクションの末尾に追加します。リンクされたレイアウトスライドもコピーされます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 複製するスライド。 |

**戻り値:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 追加されたスライド。

### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

指定されたマスタースライドのコピーをコレクションの指定位置に挿入します。リンクされたレイアウトスライドもコピーされます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 新しいスライドのインデックス。 |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 複製するスライド。 |

**戻り値:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 挿入されたマスタースライド。