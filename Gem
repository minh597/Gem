local Players = game:GetService("Players")
local player = Players.LocalPlayer

-- Copy link vào clipboard
setclipboard("https://discord.gg/K2pQX56n")

-- Tạo ScreenGui
local screenGui = Instance.new("ScreenGui")
screenGui.ResetOnSpawn = false
screenGui.Parent = player:WaitForChild("PlayerGui")

-- Tạo TextLabel
local textLabel = Instance.new("TextLabel")
textLabel.Size = UDim2.new(0.8, 0, 0.1, 0) -- chiếm 80% ngang, cao 10%
textLabel.Position = UDim2.new(0.1, 0, 0.45, 0) -- canh giữa
textLabel.BackgroundTransparency = 1
textLabel.Text = "Join our Discord for more information"
textLabel.TextColor3 = Color3.fromRGB(255, 0, 0) -- đỏ cảnh báo
textLabel.TextStrokeTransparency = 0.5
textLabel.Font = Enum.Font.SourceSansBold
textLabel.TextScaled = true -- chữ tự scale vừa khung
textLabel.Parent = screenGui

-- Hiệu ứng nhấp nháy
task.spawn(function()
    while task.wait(0.5) do
        textLabel.Visible = not textLabel.Visible
    end
end)
