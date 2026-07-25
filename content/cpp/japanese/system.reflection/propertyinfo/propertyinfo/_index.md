---
title: PropertyInfo()
second_title: Aspose.Slides for C++ API リファレンス
description: コンストラクタ。const getter のみを持つプロパティ。
type: docs
weight: 66
url: /ja/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) コンストラクタ


コンストラクタ。const getter のみを持つプロパティ。

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| PropertyType | プロパティの型です。 |
| ClassType | プロパティが属するクラスの型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | プロパティ名です。 |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | getter メソッドです。 |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) コンストラクタ


コンストラクタ。非 const getter のみを持つプロパティ。

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| PropertyType | プロパティの型です。 |
| ClassType | プロパティが属するクラスの型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | プロパティ名です。 |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | getter メソッドです。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) コンストラクタ


コンストラクタ。

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| PropertyType | プロパティの型です。 |
| ClassType | プロパティが属するクラスの型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | プロパティ名です。 |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | setter メソッドです。 |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | getter メソッドです。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) コンストラクタ


コンストラクタ。[Nullable](../../../system/nullable/) プロパティ（setter と getter あり）。

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| PropertyType | プロパティの型です。 |
| ClassType | プロパティが属するクラスの型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | プロパティ名です。 |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | setter メソッドです。 |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | getter メソッドです。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) コンストラクタ


コンストラクタ。[Nullable](../../../system/nullable/) プロパティ（const getter のみ）。

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| PropertyType | プロパティの型です。 |
| ClassType | プロパティが属するクラスの型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | プロパティ名です。 |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | setter メソッドです。 |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | getter メソッドです。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) コンストラクタ


コンストラクタ。[Object](../../../system/object/) プロパティ（getter のみ）。

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| PropertyType | プロパティの型です。 |
| ClassType | プロパティが属するクラスの型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | プロパティ名です。 |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | setter メソッドです。 |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | getter メソッドです。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) コンストラクタ


文字列プロパティ情報を構築します。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| ClassType | プロパティが属するクラスの型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | プロパティ名です。 |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | setter メソッドです。 |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | getter メソッドです。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) コンストラクタ


const getter を持つクラスから文字列プロパティ情報を構築します。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| ClassType | プロパティが属するクラスの型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | プロパティ名です。 |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | setter メソッドです。 |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | getter メソッドです。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) コンストラクタ


[Decimal](../../../system/decimal/) プロパティ情報を構築します。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| ClassType | プロパティが属するクラスの型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | プロパティ名です。 |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | setter メソッドです。 |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | getter メソッドです。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) コンストラクタ


[Decimal](../../../system/decimal/) プロパティ情報を const getter を持つクラスから構築します。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| ClassType | プロパティが属するクラスの型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | プロパティ名です。 |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | setter メソッドです。 |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | getter メソッドです。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) コンストラクタ


ブール型プロパティ情報を構築します。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| ClassType | プロパティが属するクラスの型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | プロパティ名です。 |
| set_prop_method | void(ClassType::*)(**bool**) | setter メソッドです。 |
| get_prop_method | **bool**(ClassType::*)() | getter メソッドです。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) コンストラクタ


const getter を持つクラスからブール型プロパティ情報を構築します。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| ClassType | プロパティが属するクラスの型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | プロパティ名です。 |
| set_prop_method | void(ClassType::*)(**bool**) | setter メソッドです。 |
| get_prop_method | **bool**(ClassType::*)() const | getter メソッドです。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) コンストラクタ


**int64_t** プロパティ情報を構築します。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| ClassType | プロパティが属するクラスの型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | プロパティ名です。 |
| set_prop_method | void(ClassType::*)(**int64_t**) | setter メソッドです。 |
| get_prop_method | **int64_t**(ClassType::*)() | getter メソッドです。 |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) コンストラクタ


const getter を持つクラスから **int64_t** プロパティ情報を構築します。

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| ClassType | プロパティが属するクラスの型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | プロパティ名です。 |
| set_prop_method | void(ClassType::*)(**int64_t**) | setter メソッドです。 |
| get_prop_method | **int64_t**(ClassType::*)() const | getter メソッドです。 |

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [PropertyInfo](../)
* クラス [Nullable](../../../system/nullable/)
* クラス [Decimal](../../../system/decimal/)
* 名前空間 [System::Reflection](../../)
* ライブラリ [Aspose.Slides](../../../)