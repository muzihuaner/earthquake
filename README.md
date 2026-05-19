# 快点实时地震监测系统

基于 Web 的实时地震监测与预警数据展示平台，整合中国、日本及全球地震监测数据源。

## 功能特性

- **实时震度地图** - 基于 Mapbox 展示全球地震分布与预警信息
- **最新地震速报** - 实时展示中国地震台网最新地震数据
- **日本地震情报** - 整合日本气象厅 (JMA) 地震信息
- **震动监测** - Raspberry Shake 网络实时震动波形监测
- **地震直播** - B站实时地震观测直播

## 项目结构

```
DZYJ/
├── index.html          # 主入口页面
├── CEIV2-bousai/       # 实时震度地图模块
├── CENCEQList/         # 中国地震台网数据列表
├── LocalShindo/        # 本地震动监测显示
└── .github/            # GitHub Actions 配置
```

## 数据来源

- 中国地震台网中心 (CENC)
- 日本气象厅 (JMA)
- 美国地质调查局 (USGS)
- Raspberry Shake 地震监测网络
- Wolfx 地震速报 API

## 技术栈

- HTML5 + CSS3 (Tailwind CSS)
- Mapbox GL JS
- Vanilla JavaScript (jQuery)
- D3.js (数据可视化)



## 参考项目

- [bs.wolfx.jp](https://bs.wolfx.jp) - Wolfx 地震速报




