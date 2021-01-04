### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry && availableTime < 20) {
    console.log("You should eat in the back in the lab or kitchen, where you can get to know your fellow classmates.");
  } else if (hungry && availableTime >= 20 && availableTime <= 30) {
    console.log("You deserve a break and should try a place in Gastown.");
  } else if (hungry && availableTime > 30) {
    console.log("Reminder this is a bootcamp after all and you should probably reconsider.");
  } else {
    console.log("You should wait until you're hungry if you're not.");
  }
};
```