---
title: IBehavior
second_title: Aspose.Slides for Android via Java API Reference
description: エフェクトの基本クラス ビヘイビアを表します。
type: docs
url: /ja/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

エフェクトの基本クラス ビヘイビアを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | アニメーション ビヘイビアが累積されるかどうかを表します。 |
| [setAccumulate(byte value)](#setAccumulate-byte-) | アニメーション ビヘイビアが累積されるかどうかを表します。 |
| [getAdditive()](#getAdditive--) | 現在のアニメーション ビヘイビアが他の実行中アニメーションと結合されるかどうかを表します。 |
| [setAdditive(int value)](#setAdditive-int-) | 現在のアニメーション ビヘイビアが他の実行中アニメーションと結合されるかどうかを表します。 |
| [getProperties()](#getProperties--) | ビヘイビアのプロパティを表します。 |
| [getTiming()](#getTiming--) | エフェクト ビヘイビアのタイミング プロパティを表します。 |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | エフェクト ビヘイビアのタイミング プロパティを表します。 |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

アニメーション ビヘイビアが累積されるかどうかを表します。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

アニメーション ビヘイビアが累積されるかどうかを表します。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

現在のアニメーション ビヘイビアが他の実行中アニメーションと結合されるかどうかを表します。 読み取り/書き込み [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)。

**戻り値:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

現在のアニメーション ビヘイビアが他の実行中アニメーションと結合されるかどうかを表します。 読み取り/書き込み [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

ビヘイビアのプロパティを表します。 読み取り専用 [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)。

**戻り値:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

エフェクト ビヘイビアのタイミング プロパティを表します。 読み取り/書き込み [ITiming](../../com.aspose.slides/itiming)。

**戻り値:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

エフェクト ビヘイビアのタイミング プロパティを表します。 読み取り/書き込み [ITiming](../../com.aspose.slides/itiming)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |