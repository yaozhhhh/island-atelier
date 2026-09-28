# 屿生 · Island Atelier

手机优先的风格化 3D 造岛小游戏，使用 GitHub Pages 发布静态网页。

首次进入从空海开始；点击或拖拽造陆，自动生成草地、椰树、藤蔓和海岸石块。可添加海鸥、小船和瀑布，支持双指缩放/环顾、撤销/重做、音效和背景音乐。

## 网站

部署地址由 GitHub Pages 设置确定。发布源为 `main` 分支的 `/docs` 目录。

## 本地查看

```sh
python3 -m http.server 4173 --bind 127.0.0.1 --directory docs
```

打开 <http://127.0.0.1:4173/>。需要 WebGL；声音在首次点击后启用。作品保存在当前浏览器，清除网站数据或更换设备后无法同步恢复。

## 更新

将网站文件更新到 `docs/` 并推送到 `main`，GitHub Pages 会重新发布。所有运行资源随网站存放，不依赖外部 CDN。

## 素材许可

- Three.js 0.160.1：MIT，见 `docs/vendor/THREE-LICENSE.txt`。
- 海鸥叫声：CC0，录音来源及处理信息见 `docs/audio/SEAGULL-LICENSE.md`。
- 其他音效及《海风慢慢》背景音乐为本项目合成素材。
