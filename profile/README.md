# PageHelper

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/pagehelper/Mybatis-PageHelper?style=flat-square)](https://github.com/pagehelper/Mybatis-PageHelper/stargazers)
[![Maven central](https://img.shields.io/maven-central/v/com.github.pagehelper/pagehelper?style=flat-square)](https://mvnrepository.com/artifact/com.github.pagehelper/pagehelper)
[![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/pagehelper/Mybatis-PageHelper/blob/master/LICENSE)

MyBatis 分页插件 - PageHelper

[官方文档](https://pagehelper.github.io/) | [English](https://github.com/pagehelper/Mybatis-PageHelper/blob/master/README_en.md)

</div>

## 🚀 关于 PageHelper

PageHelper 是一个 MyBatis 通用分页插件，支持任何复杂的单表、多表分页查询。通过简单的配置和使用，即可实现数据库物理分页。

### ✨ 主要特性

- 🎯 **通用性强** - 支持 MySQL、Oracle、PostgreSQL、SQLServer 等多种数据库
- 🔧 **使用简单** - 只需要一行代码即可实现分页功能
- ⚡ **性能优越** - 采用物理分页，性能优异
- 🛠️ **功能完善** - 支持排序、分页参数合理化等多种实用功能
- 📦 **零依赖** - 不依赖其他第三方插件
- 🔌 **易于集成** - 与 Spring Boot 无缝集成

## 📚 核心项目

| 项目 | 描述 | Stars |
|------|------|-------|
| [Mybatis-PageHelper](https://github.com/pagehelper/Mybatis-PageHelper) | MyBatis 分页插件 | ![GitHub stars](https://img.shields.io/github/stars/pagehelper/Mybatis-PageHelper?style=social) |
| [pagehelper-spring-boot](https://github.com/pagehelper/pagehelper-spring-boot) | PageHelper Spring Boot Starter | ![GitHub stars](https://img.shields.io/github/stars/pagehelper/pagehelper-spring-boot?style=social) |

## 🎓 快速开始

```java
// 在查询之前设置分页参数
PageHelper.startPage(1, 10);
List<User> list = userMapper.selectAll();
// 使用 PageInfo 对结果进行包装
PageInfo<User> page = new PageInfo<>(list);
```

## 🌍 社区

- 💬 [讨论区](https://github.com/pagehelper/Mybatis-PageHelper/discussions) - 提问和讨论
- 🐛 [问题反馈](https://github.com/pagehelper/Mybatis-PageHelper/issues) - 报告 Bug 和建议
- 📖 [官方文档](https://pagehelper.github.io/) - 详细的使用文档

## 🤝 贡献

欢迎提交 Pull Request 或者 Issue 来帮助改进项目！

---

<div align="center">

**感谢所有贡献者的支持！**

Made with ❤️ by PageHelper Team

</div>
