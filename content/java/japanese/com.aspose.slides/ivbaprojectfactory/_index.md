---
title: IVbaProjectFactory
second_title: Aspose.Slides for Java API Reference
description: COMインターフェイスを使用してVBAプロジェクトを作成できます
type: docs
url: /ja/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

COMインターフェイスを使用してVBAプロジェクトを作成できます
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | 新しいVBAプロジェクトを作成します。 |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | OLEコンテナからVBAプロジェクトを読み取ります。 |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```

新しいVBAプロジェクトを作成します。

**戻り値:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 新しいVBAプロジェクト
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```

OLEコンテナからVBAプロジェクトを読み取ります。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| data | byte[] | Oleデータ byte[] |

**戻り値:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - 読み取ったVBAプロジェクト