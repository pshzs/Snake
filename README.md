# 贪吃蛇qwq

**控制台贪吃蛇**

#### 2021-3-29 update ： demo 2.0

1.用goto-xy函数代替CLS清屏，避免延时闪动
2. 重构后增加拓展性

## 主要实现逻辑 ：
1. 方向键控制蛇头方向，蛇自动前进
2. 蛇头触碰边界判断死亡
3. 蛇头触碰自己判断死亡
4. 蛇头吃到食物，蛇身 + 1，分数++
5. 每局结束后统计分数，更新历史最高分，r键重新开始游戏

