---
title: DtdProcessing
second_title: Aspose.Slides for C++ APIリファレンス
description: DTD の処理オプションを指定します。DtdProcessing 列挙型は XmlReaderSettings クラスで使用されます。
type: docs
weight: 638
url: /ja/system.xml/dtdprocessing/
---
## DtdProcessing 列挙型

DTD の処理オプションを指定します。DtdProcessing 列挙型は [XmlReaderSettings](../xmlreadersettings/) クラスで使用されます。

```cpp
enum class DtdProcessing
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Prohibit | 0 | DTD が検出された場合、DTD が禁止されている旨のメッセージを伴う XmlException がスローされることを指定します。これはデフォルトの動作です。 |
| Ignore | 1 | DOCTYPE 要素が無視されます。DTD の処理は行われず、出力時に DTD/DOCTYPE は失われます。 |
| Parse | 2 | DTD の解析に使用されます。 |

## 参照

* 名前空間 [System::Xml](../)
* ライブラリ [Aspose.Slides](../../)