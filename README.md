中国所有城市信息。

数据格式如下：

```
{
  cn: { // 简体中文
    '北京': { // 中文名
      cnName: '北京', // 名称
      pyName: 'beijing', // 拼音
      capital: '北京' // 省会
    },
    ...
    ...
    '吉林': {
       'cnName':'吉林',
       'pyName':'jilin1',
       'center':'吉林',
       'x':'372', // 到市一级可以获得gps信息
       'y':'210',
       'url':'101060201', // weather.com所给出的编号
       'superCity':'吉林' // 上级省市自治区
    }
  },
  py: { // 拼音
    ...
    ...
  }
}
```

## Installation

```
npm install chinesecities
```

## usage

```
var chinesecities= require('chinesecities');
console.log(chinesecities.cn['北京']);
console.log(chinesecities.py['beijing']);
```
