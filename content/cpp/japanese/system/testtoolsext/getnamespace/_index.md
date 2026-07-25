---
title: GetNamespace()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたテストの名前空間を取得します。
type: docs
weight: 14
url: /ja/system/testtoolsext/getnamespace/
---
## TestToolsExt::GetNamespace(const char *, const char *, std::string\&) method

指定されたテストの名前空間を取得します。

```cpp
static bool System::TestToolsExt::GetNamespace(const char *class_name, const char *method_name, std::string &name_space)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| class_name | const char * | 検索対象のクラス。 |
| method_name | const char * | 検索対象のメソッド。 |
| name_space | std::string\& | 見つかった場合に名前空間名を格納する変数。 |

### 戻り値

テストメソッドが見つかった場合は true、そうでない場合は false。

## 関連項目

* 構造体 [TestToolsExt](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)