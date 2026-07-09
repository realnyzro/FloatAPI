# FloatAPI Velocity Usage Tutorial

## !! NOTE: This API only works in modern .NET so it will not work in .NET Framework

1. Add FloatAPI.dll as a reference to your project
   
2. You need to put `using FloatAPI;` at the top of your code

3. Put `FloatAPI.FloatModule.Init();` after `InitializeComponent();`

4. API Functions:

  ```FloatAPI.FloatModule.Attach();```
    - Attaches to Roblox

  `FloatAPI.FloatModule.Execute(script here);`
    - Executes a script

  `FloatAPI.FloatModule.KillRoblox();`
    - Kills Roblox process

  `FloatAPI.FloatModule.IsAttached();`
    - Returns if the API is attached (true or false)


