# powershell-config

1. Access https://ohmyposh.dev/docs/installation/windows => swtich winget to install
2. Download & install front from https://www.nerdfonts.com/
3. Create `$profile`
4. Paste oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH\jandedobbeleer.omp.json" | Invoke-Expression => auto start oh-my-posh when open powershell
5. Inatall https://www.powershellgallery.com/packages/Terminal-Icons/0.9.0 
   Import-Module -Name Terminal-Icons in `$profile`
6. Inatall https://www.powershellgallery.com/packages/PSReadLine/2.2.5 
   Import-Module -Name PSReadLine

   Set-PSReadLineOption -PredictionSource History
   Set-PSReadLineOption -PredictionViewStyle ListView
   Set-PSReadLineOption -EditMode Window in `$profile`
