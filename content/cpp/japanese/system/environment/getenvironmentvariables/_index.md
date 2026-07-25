---
title: GetEnvironmentVariables()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のプロセスに関連付けられたすべての環境変数名とその値を含むディクショナリを返します。
type: docs
weight: 326
url: /ja/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() メソッド


現在のプロセスに関連付けられたすべての環境変数名とその値を含むディクショナリを返します。

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) メソッド


指定された場所からすべての環境変数名とその値を含むディクショナリを返します。

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | 変数の場所 |

### 戻り値

指定された場所からすべての環境変数名とその値を含むディクショナリ

## 参照

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Class [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* Class [String](../../string/)
* Struct [Environment](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)