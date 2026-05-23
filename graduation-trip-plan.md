# Graduation Trip 规划档案

更新日期：2026-05-23  
来源：Claude 项目“建立旅行偏好档案”的已恢复对话与 HTML artifact；后续修正和新增内容由当前工作区维护。

## 原始材料

| 文件 | 内容 | 状态 |
| --- | --- | --- |
| `archive/claude-conversation.json` | Claude 会话完整缓存恢复稿，32 条消息 | 原始归档，不编辑 |
| `archive/claude-original-dashboard.html` | Claude 输出的 Notion 风格 dashboard | 原始归档，不编辑 |
| `index.html` | dashboard 可维护副本 | 已继续更新 |

## Claude 中已确认的偏好

| 项目 | 用户明确表达的内容 |
| --- | --- |
| 初始时间 | 2026-05-29 至 2026-06-11；随后说明毕业典礼为 2026-06-13，可从 Highway 1 返回后在 Santa Barbara 缓冲 |
| 人员 | 你、父母、男友；父母 2026-05-29 16:30 落地 LAX；男友 2026-06-03 11:29 抵达 LAX 后加入 |
| 预算 | 行程共同支出控制在约 `$10,000` |
| 目的地 | San Diego、Los Angeles、Yosemite、San Francisco、一号公路景点，终点 Santa Barbara 毕业典礼 |
| 住宿 | Airbnb 为主；需要酒店时希望每间房每晚 `$200` 以内；不希望频繁换住宿 |
| 餐饮 | 愿意大胆尝试当地特色；民宿可简单烹饪 |
| 摄影 | 以手机拍摄，但你非常重视人像、光线、服装和妆容，会为拍摄安排时间 |
| 购物 | 仅顺路购买有纪念意义的小物，不专程购物 |
| 交通 | 全程自驾 Macan；你和男友均有驾照，男友加入后主要承担长途；需留充分休息并考虑加油 |
| 体力限制 | 父母同行需舒缓节奏；不做极限运动、不安排长距离徒步或连续奔波 |

内部参考（不在 Dashboard 人物卡展示）：妈妈出生于 1968 年，爸爸出生于 1962 年；此前 Claude 记录的年份有误。

## 已预订航班

| 旅客 | 日期 | 航段 | 航班与时间 | 状态/备注 |
| --- | --- | --- | --- | --- |
| 父母 | 2026-05-29 | WUH → HKG → LAX | CX937 `12:25–14:45`；CX882 `18:25–16:30`（同日抵达 LAX） | 用户确认父母已订；PDF 所示舱等 Economy |
| 父母 | 2026-06-15 至 2026-06-16 | LAX → HKG → WUH | CX883 `00:25–05:45 (+1)`；CX924 `09:00–11:05` | 用户确认父母已订；6/16 抵达武汉 |
| 男友 | 2026-06-03 | ORD → LAX | United Economy (T) `08:51–11:29`，4h 38m | 已订 |

## 已形成的路线

| 日期 | 住宿/转场 | 工作版安排重点 |
| --- | --- | --- |
| 05/29 Fri | LAX → San Diego | 16:30 接父母后直达住宿，傍晚仅转场 |
| 05/30 Sat | San Diego | 适应时差，La Jolla 轻松散步和日落拍摄 |
| 05/31 Sun | San Diego | Balboa Park + Old Town |
| 06/01 Mon | San Diego | Coronado 慢游，预留整理和自炊时间 |
| 06/02 Tue | San Diego → Los Angeles | 退房与入住为主 |
| 06/03 Wed | Los Angeles | 11:29 LAX 接男友后会合，保留轻松活动弹性 |
| 06/04 Thu | Los Angeles | Getty Center + Griffith 日落拍摄 |
| 06/05 Fri | Los Angeles → Yosemite | 长途驾驶日，预计约 5.5–6.5 小时加停靠 |
| 06/06 Sat | Yosemite | Valley 轻量步行、瀑布与日落机位 |
| 06/07 Sun | Yosemite | 可选清晨机位 + 短线步行/休息 |
| 06/08 Mon | Yosemite → San Francisco | 转场日，预计约 4–4.5 小时 |
| 06/09 Tue | San Francisco | 金门桥、Chinatown、Pier 39；Alcatraz 作为可选主活动 |
| 06/10 Wed | San Francisco → Carmel | 午后启程沿海岸驾驶；在 Carmel 夜宿以减少折腾 |
| 06/11 Thu | Carmel → Santa Barbara | Highway 1 景观驾驶日，经 Big Sur / 象海豹观景点返回 |
| 06/12 Fri | Santa Barbara | 典礼前休息、整理行李和正式服 |
| 06/13 Sat | Santa Barbara | 毕业典礼 |

## Claude 原 dashboard 已有模块

已填充：Dashboard、Itinerary、Route Planning、Attractions、Hotels & Airbnb、Reservations、Photography、Budget Tracker、Task List。

Claude 尚未填充：Restaurants、Google Maps、Outfit Planning。

当前工作版新增：饮食/补给框架、六段导航入口、四组摄影场景穿搭和毕业典礼准备清单。

## 景点筛选阶段

2026-05-23 起，`Attractions` 模块改为候选池模式，不在本阶段生成最终名单或每日行程。

- 覆盖目的地：San Diego、Los Angeles、Yosemite、San Francisco、Highway 1 / Carmel / San Simeon。
- 分类维度：必去地标、海景景点、摄影圣地、城市漫步、博物馆、自然景观、适合父母的轻松景点、美食区域。
- 卡片信息：一句话亮点、值得前往原因、推荐停留时间、当地代表性、Google Maps、官方网站与景点图片。
- 选择方式：Dashboard 内可勾选“想去”，选择存储在当前浏览器本地；待用户完成筛选后，再以必选点为中心讨论顺路补充与行程安排。
- Yosemite 作为核心目的地，候选项扩展至 Valley 轻量景点、瀑布、经典摄影机位、Glacier Point 以及 Tioga Road 高地候选。
- San Diego 待确认约束：`San Diego Zoo` 与 `Birch Aquarium at Scripps` 至少选一个进入后续行程；两者目前均保留为候选，不预排日期。
- San Diego 明确兴趣：`Seaport Village & Embarcadero` 已加入候选池并标记为用户想去。

## 已核验并修正的事项

1. Claude dashboard 把 2026 日期配成了 2025 的星期。工作版已按 2026 日历更正，例如 `2026-05-29` 为周五，`2026-06-13` 为周六；原始 artifact 保持未改。
2. Claude 把 `Yosemite Timed Entry Permit` 视为需要抢购的紧急任务。NPS 于 2026-02-18 宣布 Yosemite 在 2026 年不使用 timed reservation system，工作版已移除该待办并保留住宿优先级。
3. NPS 当前说明 Yosemite 对每名 16 岁以上非美国居民加收 `$100`，除非由有效的适用通行证覆盖。同行者居民/通行证状态未在 Claude 对话中确认，现列为预算待办。
4. Claude 的 `LA → Yosemite` 与 `Yosemite → SF` 驾车时间偏短，工作版已调整为更保守的长途日估计，并避免在抵达日安排重活动。
5. Caltrans 于 2026-01-14 重开 Regent's Slide 路段，当前路线可按 Highway 1 规划；因山体滑坡与天气会改变状态，工作版要求 2026-06-10 出发前再次复查道路情况并保留 US-101 备选。
6. 工作版的预估共同支出当前为 `$6,900`，预算缓冲为 `$3,100`。
7. NPS 当前状态页（更新于 2026-05-21）显示 Yosemite Valley Roads、Glacier Point Road 与 Tioga Road 均开放；候选池仍将高地景点标注为需临近出发复查状态。
8. 用户提供的机票资料显示父母于 2026-05-29 `16:30` 抵达 LAX，而非此前记录的 `18:30`；工作版已更正，并记录父母返程与男友抵达航班均已预订。

## 当前待决策清单

| 优先级 | 事项 | 需要确定的信息 |
| --- | --- | --- |
| 立即 | Yosemite 三晚住宿 | 园内 / El Portal 可接受价格、可取消库存 |
| 立即 | 男友抵达接机衔接 | 2026-06-03 11:29 于 LAX 抵达；确定接客点与当天轻量安排 |
| 立即 | Yosemite 入园预算 | 四人居民身份与已有通行证状态 |
| 尽快 | SD、LA、SF Airbnb 与 Carmel 酒店 | 2 卧室/两间房、停车、厨房、总价 |
| 尽快 | Alcatraz 或 Hearst Castle 是否加入 | 二者都会占用较完整时段，需要按父母体力取舍 |
| 出发前 | Highway 1 路况 | 若临时封路，改走 US-101 返回 SB |

## 官方核验来源

- [Yosemite 2026 vehicle reservation announcement](https://www.nps.gov/yose/learn/news/yosemite-national-park-will-not-require-vehicle-reservations-in-2026.htm)
- [Yosemite fees and passes](https://www.nps.gov/yose/planyourvisit/fees.htm)
- [NPS nonresident fees](https://www.nps.gov/aboutus/nonresident-fees.htm)
- [Caltrans Highway 1 Regent's Slide reopening announcement](https://dot.ca.gov/caltrans-near-me/district-5/d5-news/d5-news-1-14-26)
- [Caltrans QuickMap for current road conditions](https://quickmap.dot.ca.gov/)
