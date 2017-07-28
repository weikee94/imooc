# course
- [初识react native](http://www.imooc.com/video/14286) (27 July 2017)

# get started 
- nodeJS
- react native command line tools (npm install -g react-native-cli)
- xCode/androidStudio

# initial project
- react-native init FirstApp
- react-native run-ios
- react-native run-android

# nuclide for atom + watchman service

# What is React Components?
- react components are reusable (Header, Tabs, Item, tabBar)
- three ways to create component (ES6, ES5, Function)

# Write Component
- ES6
    ```
    export default class HelloComponent extends Component {
        render() {
            return <Text style={{fontSize:20,backgroundColor:'red'}}>Hello</Text>
        }
    }
    ```
- ES5
    ```
    var HelloComponent = React.createClass({
        render() {
            return <Text styl{{fontSize:20,backgroundColor:'red'}}Hello</Text>
        }
    })
    module.exports = HelloComponent;
    ```

# All the class must be capitalize else will throw a expected-a-component-class error