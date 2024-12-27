# 天光云影配置说明

#### 配置文件
[default.json](https://gitee.com/xdozhao/iptv/raw/master/tgyy/config/default.json)
#### 配置说明
```aiignore
{
  // 版本号
  "version": "3.3.7",
  //时间戳
  "syncAt": 1735309277085,
  // 配置名称
  "syncFrom": "天光云影配置",
  //配置描述
  "description": null,
  "configs": {
    // 开机自启
    "appBootLaunch": false,
    "appPipEnable": false,
    "appLastLatestVersion": "",
    "appAgreementAgreed": true,
    "appStartupScreen": "Dashboard",
    // 开发者模式
    "debugDeveloperMode": false,
    // FPS显示
    "debugShowFps": false,
    // 显示播放器信息
    "debugShowVideoPlayerMetadata": false,
    // 显示布局网格
    "debugShowLayoutGrids": false,
    // 直播源缓存时间
    "iptvSourceCacheTime": 86400000,
    // 当前直播源
    "iptvSourceCurrent": {
      // 名称
      "name": "默认直播源（IPV6）",
      // 链接
      "url": "https://live.fanmingming.cn/tv/m3u/ipv6.m3u",
      // 本地文件
      "isLocal": false,
      // 转换JS
      "transformJs": null
    },
    // 直播源列表
    "iptvSourceList": {
      "value": [
        {
          "name": "默认直播源（IPV6）",
          "url": "https://live.fanmingming.cn/tv/m3u/ipv6.m3u",
          "isLocal": false,
          "transformJs": null
        },
        {
          "name": "电视直播",
          "url": "https://tv.iill.top/m3u/Gather",
          "isLocal": false,
          "transformJs": null
        },
        {
          "name": "网络直播",
          "url": "https://tv.iill.top/m3u/Live",
          "isLocal": false,
          "transformJs": null
        },
        {
          "name": "体育直播",
          "url": "https://tv.iill.top/m3u/Sport",
          "isLocal": false,
          "transformJs": null
        },
        {
          "name": "MyTV直播",
          "url": "https://tv.iill.top/m3u/MyTV",
          "isLocal": false,
          "transformJs": null
        }
      ]
    },
    // 频道分组隐藏
    "iptvChannelGroupHiddenList": [],
    // iptv混合模式
    "iptvHybridMode": "DISABLE",
    // 相似频道合并
    "iptvSimilarChannelMerge": false,
    // 频道图标提供
    "iptvChannelLogoProvider": "https://live.fanmingming.cn/tv/{name|uppercase}.png",
    // // 频道图标提供
    "iptvChannelLogoOverride": false,
    // iptv频道收藏夹启用
    "iptvChannelFavoriteEnable": true,
    "iptvChannelFavoriteListVisible": false,
    "iptvChannelFavoriteList": {
      "value": []
    },
    "iptvChannelLastPlay": null,
    "iptvChannelLinePlayableHostList": null,
    "iptvChannelLinePlayableUrlList": null,
    "iptvChannelChangeFlip": false,
    "iptvChannelNoSelectEnable": true,
    "iptvChannelChangeListLoop": false,
    "epgEnable": true,
    "epgSourceCurrent": {
      "name": "默认节目单 fanmingming",
      "url": "https://live.fanmingming.cn/e.xml"
    },
    "epgSourceList": {
      "value": []
    },
    "epgRefreshTimeThreshold": 2,
    "epgSourceFollowIptv": false,
    "epgChannelReserveList": {
      "value": []
    },
    "uiShowEpgProgrammeProgress": true,
    "uiShowEpgProgrammePermanentProgress": false,
    "uiShowChannelLogo": true,
    "uiShowChannelPreview": false,
    "uiUseClassicPanelScreen": false,
    "uiDensityScaleRatio": 0,
    "uiFontScaleRatio": 1,
    "uiTimeShowMode": "HIDDEN",
    "uiFocusOptimize": true,
    "uiScreenAutoCloseDelay": 15000,
    "updateForceRemind": false,
    "updateChannel": "stable",
    "videoPlayerCore": "MEDIA3",
    "videoPlayerRenderMode": "SURFACE_VIEW",
    "videoPlayerUserAgent": "okhttp",
    "videoPlayerHeaders": "",
    "videoPlayerLoadTimeout": 15000,
    "videoPlayerDisplayMode": "ORIGINAL",
    "videoPlayerForceAudioSoftDecode": false,
    "videoPlayerStopPreviousMediaItem": false,
    "videoPlayerSkipMultipleFramesOnSameVSync": true,
    "themeAppCurrent": null,
    "cloudSyncAutoPull": null,
    "cloudSyncProvider": null,
    "cloudSyncGithubGistId": null,
    "cloudSyncGithubGistToken": null,
    "cloudSyncGiteeGistId": null,
    "cloudSyncGiteeGistToken": null,
    "cloudSyncNetworkUrl": null,
    "cloudSyncLocalFilePath": null,
    "cloudSyncWebDavUrl": null,
    "cloudSyncWebDavUsername": null,
    "cloudSyncWebDavPassword": null,
    "feiyangAllInOneFilePath": ""
  },
  "extraLocalIptvSourceList": {},
  "extraChannelNameAlias": ""
}

```

