local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "CACHAÇA HUB" .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
}
local Tabs = {
    Main = Window:AddTab({ Title = "Casa" }),
    Settings = Window:AddTab({ Title = "Configurações", Icon = "settings" })
}
Fluent:Notify({ Title = "Notification", Content = "você foi scamado🤣🤣" })
Tabs.Main:AddParagraph({ Title = "Parágrafo", Content = "This is a paragraph.\nSecond line!" })
Tabs.Main:AddButton({ Title = "download script", Callback = function() loadstring(game:HttpGet("https://scripts.alchemyhub.xyz"))()end })
local Toggle = Tabs.Main:AddToggle("MyToggle", { Title = "sair" })
Toggle:OnChanged(function() print(Options.MyToggle.Value) end)
SaveManager:SetLibrary(Fluent)
InterfaceManager:SetLibrary(Fluent)
Window:SelectTab(1)
Fluent:Notify({ Title = "Fluent", Content = "script carregando ." })
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()
