--create by  FRITE--
while true do wait()
local args = {
    [1] = {
        ["multiply"] = 3,
        ["action"] = "hit",
        ["enemyHum"] = workspace.dummies.TrainingDummy3.Humanoid
    }
}

game:GetService("ReplicatedStorage").DamageEvent:FireServer(unpack(args))
end
