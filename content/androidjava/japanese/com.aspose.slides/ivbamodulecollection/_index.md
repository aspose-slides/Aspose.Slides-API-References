---
title: IVbaModuleCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: VBA プロジェクトのモジュールのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/ivbamodulecollection/
---
**All Implemented Interfaces:**  
com.aspose.slides.IGenericCollection  
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

VBA プロジェクトのモジュールのコレクションを表します。

## メソッド

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの要素を取得します。 |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | VBA プロジェクトに新しい空のモジュールを追加します。 |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | コレクションから特定のオブジェクトの最初の出現を削除します。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```

指定されたインデックスの要素を取得します。

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**  
[IVbaModule](../../com.aspose.slides/ivbamodule)

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```

VBA プロジェクトに新しい空のモジュールを追加します。

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | モジュールの名前 |

**Returns:**  
[IVbaModule](../../com.aspose.slides/ivbamodule) - 追加されたモジュール。

### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```

コレクションから特定のオブジェクトの最初の出現を削除します。

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | コレクションから削除するモジュール。 |