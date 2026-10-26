---
title: Read()
second_title: Aspose.Slides for C++ API リファレンス
description: ストリームから単一の文字を読み取ります。
type: docs
weight: 40
url: /ja/system.io/stringreader/read/
---
## StringReader::Read() メソッド


ストリームから単一の文字を読み取ります。

```cpp
virtual int System::IO::StringReader::Read() override
```


### 戻り値

読み取られた文字、または文字が読み取れなかった場合は -1

## StringReader::Read(ArrayPtr\<char_t\>, int, int) メソッド


ストリームから指定された文字数を、指定された位置から始まる指定された文字配列に読み取ります。

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | ストリームから読み取った文字を書き込む文字配列 |
| index | int | 書き込みを開始する **buffer** 内の 0 から始まるインデックス |
| count | int | ストリームから読み取る文字数 |

### 戻り値

ストリームから読み取った文字数

## 参照

* typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [StringReader](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)