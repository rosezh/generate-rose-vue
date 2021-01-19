vue generator案例

mkdir generator-rose-vue
cd generator-rose-vue
yarn init -y
yarn add yeoman-generator
code .

# 拷贝模板到generators/app/templates下
# 入口文件 index.js完成


yarn link
cd ..
mkdir my-proj
cd my-proj
yo rose-vue //运行生成模板文件命令

# 查看my-proj文件夹，模板文件已经生成到里面



以下操作需删除之前创建的generators文件夹里的内容

# 发布generator
echo node_modules > .gitignore 创建gitignore

git init
git status    查看本地仓库的状态

