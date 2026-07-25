---
title: IsTest()
second_title: Aspose.Slides for C++ API リファレンス
description: テスト メソッドが存在するかどうかを確認します。
type: docs
weight: 1
url: /ja/system/testtoolsext/istest/
---
## TestToolsExt::IsTest(const char *, const char *, const char *) メソッド

テスト メソッドが存在するかどうかを確認します。

```cpp
static bool System::TestToolsExt::IsTest(const char *name_space, const char *class_name, const char *method_name)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| name_space | const char * | 検索する名前空間。 |
| class_name | const char * | 検索するクラス。 |
| method_name | const char * | 検索するメソッド。 |

### 戻り値

テスト メソッドが登録されている場合は true、そうでない場合は false です。

## TestToolsExt::IsTest(const char *, const char *) メソッド

テスト メソッドが存在するかどうかを確認します。

```cpp
static bool System::TestToolsExt::IsTest(const char *class_name, const char *method_name)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| class_name | const char * | 検索するクラス。 |
| method_name | const char * | 検索するメソッド。 |

### 戻り値

テスト メソッドが登録されている場合は true、そうでない場合は false です。

## 参照

* 構造体 [TestToolsExt](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)