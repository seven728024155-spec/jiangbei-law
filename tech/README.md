# 技术文档 🔧

欢迎来到江北法律咨询公司的技术中心！

## 🛠️ 技术栈

### 前端技术
- **框架**：React / Vue.js
- **UI 组件**：Ant Design / Element Plus
- **状态管理**：Redux / Pinia
- **构建工具**：Vite / Webpack

### 后端技术
- **语言**：Python / Node.js / Go
- **框架**：FastAPI / Express / Gin
- **数据库**：PostgreSQL / MongoDB / Redis
- **搜索引擎**：Elasticsearch

### AI/ML 技术
- **大语言模型**：OpenAI GPT / Claude / 文心一言
- **向量数据库**：Pinecone / Milvus / Chroma
- **NLP 工具**：spaCy / NLTK / HanLP

### 运维与部署
- **容器化**：Docker / Kubernetes
- **CI/CD**：GitHub Actions / GitLab CI
- **监控**：Prometheus / Grafana
- **日志**：ELK Stack / Loki

---

## 📂 代码规范

### Git 分支管理
```
main
  ├── develop
  │     ├── feature/lawbot-ui
  │     ├── feature/contract-check
  │     └── bugfix/login-issue
  └── release/v1.0.0
```

### 提交信息规范
```
<type>(<scope>): <subject>

类型：
- feat: 新功能
- fix: 修复 bug
- docs: 文档更新
- style: 代码格式调整
- refactor: 重构
- test: 测试相关
- chore: 构建/工具相关
```

### 代码审查清单
- [ ] 代码符合项目规范
- [ ] 有足够的测试覆盖
- [ ] 文档已更新
- [ ] CI 检查通过
- [ ] 至少一人审核通过

---

## 🚀 部署流程

### 开发环境
```bash
# 本地开发
docker-compose -f docker-compose.dev.yml up

# 代码提交
git add .
git commit -m "feat: add new feature"
git push origin feature/xxx
```

### 测试环境
```bash
# 创建 PR
gh pr create --base develop --head feature/xxx

# 自动部署到测试环境
# GitHub Actions 自动触发
```

### 生产环境
```bash
# 合并到 main 分支
git checkout main
git merge release/v1.0.0

# 自动部署到生产环境
# GitHub Actions 自动触发
```

---

## 🔒 安全规范

### 数据安全
- 所有敏感数据加密存储
- 数据库访问使用最小权限原则
- 定期备份数据

### API 安全
- 使用 HTTPS
- JWT / OAuth2.0 认证
- API 限流和防刷
- 输入验证和 SQL 注入防护

### 代码安全
- 定期进行安全审计
- 依赖项安全扫描
- 敏感信息不提交到代码库

---

## 📞 技术支持

### 遇到问题？
1. **查看文档** - 先检查本文档是否有解决方案
2. **搜索 Issues** - 看看是否有人遇到过类似问题
3. **创建 Issue** - 如果没有找到答案，创建新 Issue
4. **@技术负责人** - 紧急问题可以直接 @戴特 🦞

### 技术负责人
- **戴特** 🦞 - 全栈程序员，解决一切技术难题

---

*让技术成为法律的翅膀！* 🦅
