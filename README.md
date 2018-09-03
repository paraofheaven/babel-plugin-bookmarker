# babel-plugin-bookmarker
A little bookmarker for babel plugin learning

##### project-wide configuration
The primary downside of this project-wide config is that, because it relies on the working directory, it can be more painful to use in monorepos if the working directory is not the monorepo root.

configurations in .babelrc would be compiled form the node_modules,and support for project name:
 ```.babelrc
  plugins:[
    'react-loadable/babel'
  ]
 ```
 which will parse the node-modules/react-loadable/babel.
 
