# Calc

## HOW TO USE IT:
- Using the terminal run `iex -S mix` on then project directory path.
- With the compiled code you can now run the following.
- To get the PID of the project run `pid = Calc.start()`
- Then using the pid you can add values substract them and multiply and also divide them.
- Output example: 
           `iex(1)> pid = Calc.start()
            #PID<0.171.0>
            iex(2)> Calc.add(pid,10)
            {:add, 10}
            iex(3)> Calc.sub(pid, 10-2)
            {:sub, 8} `
"# simple-calculator-using-elixir" 
