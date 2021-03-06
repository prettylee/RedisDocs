## 为什么会有Redis ##
### 出现问题场景 ###
- 海量用户
- 高并发
### 原因 ###
关系性数据库存在以下缺点：
- 性能瓶颈：磁盘IO性能差
- 扩展性能：数据关系复杂，不利于扩展
### 解决思路 ###
- 减低磁盘IO —内存存储
- 简化数据关系—不存关系只存数据

## Nosql简介 ##
- Not-Only SQL，泛指非关系型数据库，作为关系性数据库的补充。
- 作用：应对海量用户和海量数据场景下的问题处理。
### 特点 ###
- 可扩展，可伸缩
- 大数据量下的高性能
- 灵活的数据模型
- 高可用
### 常见的Nosql数据库：
- Redis
- memcache
- HBase
- MongoDB
### 解决方案 ###
1. 商品基本信息（MySql）
  - 名称
  - 价格
  - 厂商
2. 商品附加信息（MongoDB）
  - 描述
  - 详情
  - 评论
3. 图片（分布式文件系统）
4. 关键字（ES,Lucene,solr）
5. 热点信息（Redis,memcache,tair）
  - 高频
  - 波段性