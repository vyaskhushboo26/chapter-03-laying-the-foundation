# Chapter 3 laying the foundation

1. npm init -> create package.json

2. `phollyfill` - A code which is a replacement of a newer version of code

### `question` - who convert the newer version of code into th older version of code?
  `Babel` does it
  `Babel` -> is just a javascript package/library.
  babel uses `browserlist` to convert this, and we don't need to write phollyfill.
  babel automatilly does it self.

3. `git init` -> A command which will make your repository compatible with git
               and onces it done we have a access of all the like push, pull, add, commit, create branch etc.

4. `npm` -> is use when you execute a package without installing.
   `npx` -> when you want to install your package.

5. `add script` to run command
    package.json -> script -> add `start and build` script -> and become simple and easy command 
   
   ```

    "script" : {
      "start": "parcel index.html",
      "build": "parcel build index.html",
      "test" : "jest"
    }

    ```
    ### new commnd

    `npm run start` or `npm start`
    `npm run build`

 6. `plugin` to remove console log 
     ### babel plugin tranform remove console  

     directly parcel and babel does not remove console log. we have to install plugin for this and configure into your project.
    create file .babelrc -> add configuration

7.  `render` -> update something into you DOM

8. `keys` -> always gives keys to childeren and it can be anything which is uniquly identified. 
              keys passing it as a prop.

9. `React.createElement` -> gives `object` -> react convert that object into `HTML` -> and put into   `DOM`

10. `JSX` -> HTML like syntex inside js is JSX

11. `Babel` -> its a javascript compiler. which is convert JSX into react.createElement(get browser compatible javascript out) to undestand browser that ok this is a js and html code 

12. `JSX` -> `React.createElement` -> gives `object` -> react convert that object into `HTML` -> and put into   `DOM`
JSX is a syntex.and we write JSX expression in our code which is read by babel 
JSX take care of cross side scripting language


13. ## `babel come along with parcel `
when you installed parcel or any bundler, its comes as a dependency along with parcel.

* Readability
* developer exeperience
* less code
* maintability
* no reaptation
* syntatic sugar syntex

babel comes with parcel as a dependency

14. ### `React Component`

 * Functional component - new way
 * Class based component - old way

# Functional component
This is a normal javascript function which return a some peice of JSX code(it can be component it self)
Name of component start with capital leter(good practices)

# If we want to use React.createElement inside JSX then use in { }
two way of function calling
<Title /> or { Title()}

15. ## Component Composition or composing component
Use component inside component or nested component is called component composition.

Note -> When we use props then we need a functional component otherwise React.Element is enough.

Ques1. What is babel and phollyfill ?
Ans.   babel takes new peices of code and compile into old peice of code which is compatible with browser so that old peice of code is known as phollyfill.

   
    
