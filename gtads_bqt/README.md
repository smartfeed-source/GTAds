# GTAds百度百青藤广告支持插件

> 横幅广告暂不可用

<p>
<a href="https://pub.flutter-io.cn/packages/gtads_csj"><img src=https://img.shields.io/badge/gtads_bqt-v1.1.0-success></a>
</p>

# 📢 相关插件

- [baiduad](https://github.com/gstory0404/baiduad) 百青藤广告本体，内部已集成无需额外引入，配置相关查看插件说明
- [GTAds](https://github.com/gstory0404/GTAds) 聚合广告插件基础库，必须引入

# 使用

### pubspec.yaml

```dart
 //广告基础库 必须引入
 gtads: ^1.1.0
 //百青藤广告支持
 gtads_bqt: ^1.1.0
```

### 引入

```dart
import 'package:gtads_csj/gtads_bqt.dart';
```

### 使用

仅需通过以下方法插入广告至聚合插件，无需关注具体广告的调用

```dart
//参数依次为 别名、andorid app Id、ios app Id
 GTAds.addProvider([GTAdsBqtProvider("bqt", "b423d90d", "a6b7fed6")]);
```

> 广告位使用参考[GTAds](https://github.com/gstory0404/GTAds/tree/master/gtads)
