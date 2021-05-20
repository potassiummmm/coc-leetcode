# [Leetcode-cn](https://leetcode-cn.com) 插件

![image](https://user-images.githubusercontent.com/5492542/82134259-a73b0c00-9828-11ea-9c73-e4ab21c61351.png)

## 说明
LeetCode vim/neovim插件, forked from [iamcco/coc-leetcode](https://github.com/iamcco/coc-leetcode)

## 安装

使用插件管理器(如[vim-plug](https://github.com/junegunn/vim-plug))
```vim
Plug 'potassiummmm/coc-leetcode', {'do': 'yarn install --frozen-lockfile && yarn build'}
```

## 使用

查看算法题目列表

```vim
:CocList LeetcodeProblems
```

### 配置

- `leetcode.language` 使用的目标语言
- `leetcode.trace.server` 日志
- `leetcode.enabled` 是否启用
- `leetcode.filePath` 保存代码文件的路径

### 命令

- `leetcode.login` 用户名密码登录
- `leetcode.run` 执行当前代码
- `leetcode.submit` 提交当前代码
- `leetcode.comments` 查看当前算法用户评论

