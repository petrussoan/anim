	-- Gui to Lua
		-- Version: 3.2
	
		-- Instances:
	
		local ScreenGui = Instance.new("ScreenGui")
		local Animation = Instance.new("Frame")
		local UICorner = Instance.new("UICorner")
		local ScrollingFrame = Instance.new("ScrollingFrame")
		local zombie = Instance.new("TextButton")
		local UICorner_2 = Instance.new("UICorner")
		local toy = Instance.new("TextButton")
		local Superhero = Instance.new("TextButton")
		local Stylish = Instance.new("TextButton")
		local Robot = Instance.new("TextButton")
		local Pirate = Instance.new("TextButton")
		local Ninja = Instance.new("TextButton")
		local Mage = Instance.new("TextButton")
		local Astronaut = Instance.new("TextButton")
		local close = Instance.new("TextButton")
		local UICorner_3 = Instance.new("UICorner")
	
		--Properties:
	
		ScreenGui.Parent = game.CoreGui
	
		Animation.Name = "Animation"
		Animation.Parent = ScreenGui
		Animation.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
		Animation.Position = UDim2.new(0.03876739, 0, 0.181628406, 0)
		Animation.Size = UDim2.new(0, 318, 0, 304)
	
		UICorner.Parent = Animation
	
		ScrollingFrame.Parent = Animation
		ScrollingFrame.Active = true
		ScrollingFrame.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
		ScrollingFrame.BorderSizePixel = 0
		ScrollingFrame.Position = UDim2.new(0.0346494466, 0, 0.0476189665, 0)
		ScrollingFrame.Size = UDim2.new(0, 297, 0, 277)
	
		zombie.Name = "zombie"
		zombie.Parent = ScrollingFrame
		zombie.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
		zombie.BorderSizePixel = 0
		zombie.Position = UDim2.new(0.0259609967, 0, -0.00107001793, 0)
		zombie.Size = UDim2.new(0, 299, 0, 50)
		zombie.Font = Enum.Font.SourceSans
		zombie.Text = "Zombie"
		zombie.TextColor3 = Color3.fromRGB(255, 255, 255)
		zombie.TextScaled = true
		zombie.TextSize = 14.000
		zombie.TextWrapped = true
	
		UICorner_2.Parent = ScrollingFrame
	
		toy.Name = "toy"
		toy.Parent = ScrollingFrame
		toy.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
		toy.BorderSizePixel = 0
		toy.Position = UDim2.new(-0.00097503094, 0, 0.0811668262, 0)
		toy.Size = UDim2.new(0, 299, 0, 50)
		toy.Font = Enum.Font.SourceSans
		toy.Text = "Toy"
		toy.TextColor3 = Color3.fromRGB(255, 255, 255)
		toy.TextScaled = true
		toy.TextSize = 14.000
		toy.TextWrapped = true
	
		Superhero.Name = "Superhero"
		Superhero.Parent = ScrollingFrame
		Superhero.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
		Superhero.BorderSizePixel = 0
		Superhero.Position = UDim2.new(-0.00097503094, 0, 0.153535247, 0)
		Superhero.Size = UDim2.new(0, 299, 0, 50)
		Superhero.Font = Enum.Font.SourceSans
		Superhero.Text = "Superhero"
		Superhero.TextColor3 = Color3.fromRGB(255, 255, 255)
		Superhero.TextScaled = true
		Superhero.TextSize = 14.000
		Superhero.TextWrapped = true
	
		Stylish.Name = "Stylish"
		Stylish.Parent = ScrollingFrame
		Stylish.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
		Stylish.BorderSizePixel = 0
		Stylish.Position = UDim2.new(-0.000975031406, 0, 0.235772088, 0)
		Stylish.Size = UDim2.new(0, 299, 0, 50)
		Stylish.Font = Enum.Font.SourceSans
		Stylish.Text = "Stylish"
		Stylish.TextColor3 = Color3.fromRGB(255, 255, 255)
		Stylish.TextScaled = true
		Stylish.TextSize = 14.000
		Stylish.TextWrapped = true
	
		Robot.Name = "Robot"
		Robot.Parent = ScrollingFrame
		Robot.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
		Robot.BorderSizePixel = 0
		Robot.Position = UDim2.new(-0.000975031406, 0, 0.316364199, 0)
		Robot.Size = UDim2.new(0, 299, 0, 50)
		Robot.Font = Enum.Font.SourceSans
		Robot.Text = "Robot"
		Robot.TextColor3 = Color3.fromRGB(255, 255, 255)
		Robot.TextScaled = true
		Robot.TextSize = 14.000
		Robot.TextWrapped = true
	
		Pirate.Name = "Pirate"
		Pirate.Parent = ScrollingFrame
		Pirate.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
		Pirate.BorderSizePixel = 0
		Pirate.Position = UDim2.new(-0.00770903798, 0, 0.398601055, 0)
		Pirate.Size = UDim2.new(0, 299, 0, 50)
		Pirate.Font = Enum.Font.SourceSans
		Pirate.Text = "Pirate"
		Pirate.TextColor3 = Color3.fromRGB(255, 255, 255)
		Pirate.TextScaled = true
		Pirate.TextSize = 14.000
		Pirate.TextWrapped = true
	
		Ninja.Name = "Ninja"
		Ninja.Parent = ScrollingFrame
		Ninja.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
		Ninja.BorderSizePixel = 0
		Ninja.Position = UDim2.new(-0.00770903798, 0, 0.480837882, 0)
		Ninja.Size = UDim2.new(0, 299, 0, 50)
		Ninja.Font = Enum.Font.SourceSans
		Ninja.Text = "Ninja"
		Ninja.TextColor3 = Color3.fromRGB(255, 255, 255)
		Ninja.TextScaled = true
		Ninja.TextSize = 14.000
		Ninja.TextWrapped = true
	
		Mage.Name = "Mage"
		Mage.Parent = ScrollingFrame
		Mage.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
		Mage.BorderSizePixel = 0
		Mage.Position = UDim2.new(-0.00770903798, 0, 0.563074708, 0)
		Mage.Size = UDim2.new(0, 299, 0, 50)
		Mage.Font = Enum.Font.SourceSans
		Mage.Text = "Mage"
		Mage.TextColor3 = Color3.fromRGB(255, 255, 255)
		Mage.TextScaled = true
		Mage.TextSize = 14.000
		Mage.TextWrapped = true
	
		Astronaut.Name = "Astronaut"
		Astronaut.Parent = ScrollingFrame
		Astronaut.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
		Astronaut.BorderSizePixel = 0
		Astronaut.Position = UDim2.new(-0.000975031406, 0, 0.645311534, 0)
		Astronaut.Size = UDim2.new(0, 299, 0, 50)
		Astronaut.Font = Enum.Font.SourceSans
		Astronaut.Text = "Astronaut"
		Astronaut.TextColor3 = Color3.fromRGB(255, 255, 255)
		Astronaut.TextScaled = true
		Astronaut.TextSize = 14.000
		Astronaut.TextWrapped = true
	
		close.Name = "close"
		close.Parent = Animation
		close.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		close.Position = UDim2.new(0.933109879, 0, 0, 0)
		close.Size = UDim2.new(0, 21, 0, 13)
		close.Font = Enum.Font.SourceSansBold
		close.Text = "X"
		close.TextColor3 = Color3.fromRGB(0, 0, 0)
		close.TextSize = 25.000
	
		UICorner_3.Parent = close
	
		-- Scripts:
	
		local function DCTGPYH_fake_script() -- zombie.LocalScript 
			local script = Instance.new('LocalScript', zombie)
	
			script.Parent.MouseButton1Click:Connect(function()
				local Animate = game.Players.LocalPlayer.Character.Animate
				Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616158929"
				Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616160636"
				Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616168032"
				Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616163682"
				Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616161997"
				Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616156119"
				Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616157476"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end);
	
		end
		coroutine.wrap(DCTGPYH_fake_script)()
		local function BAFPSYQ_fake_script() -- toy.LocalScript 
			local script = Instance.new('LocalScript', toy)
	
			script.Parent.MouseButton1Click:Connect(function()
				local Animate = game.Players.LocalPlayer.Character.Animate
				Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=782841498"
				Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=782845736"
				Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=782843345"
				Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=782842708"
				Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=782847020"
				Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=782843869"
				Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=782846423"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)
		end
		coroutine.wrap(BAFPSYQ_fake_script)()
		local function XOFUW_fake_script() -- Superhero.LocalScript 
			local script = Instance.new('LocalScript', Superhero)
	
			script.Parent.MouseButton1Click:Connect(function()
				local Animate = game.Players.LocalPlayer.Character.Animate
				Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616111295"
				Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616113536"
				Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616122287"
				Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616117076"
				Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616115533"
				Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616104706"
				Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616108001"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)
		end
		coroutine.wrap(XOFUW_fake_script)()
		local function AFAAG_fake_script() -- Stylish.LocalScript 
			local script = Instance.new('LocalScript', Stylish)
	
			script.Parent.MouseButton1Click:Connect(function()
				local Animate = game.Players.LocalPlayer.Character.Animate
				Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616136790"
				Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616138447"
				Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616146177"
				Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616140816"
				Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616139451"
				Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616133594"
				Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616134815"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)
		end
		coroutine.wrap(AFAAG_fake_script)()
		local function LIVE_fake_script() -- Robot.LocalScript 
			local script = Instance.new('LocalScript', Robot)
	
			script.Parent.MouseButton1Click:Connect(function()
				local Animate = game.Players.LocalPlayer.Character.Animate
				Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616088211"
				Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616089559"
				Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616095330"
				Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616091570"
				Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616090535"
				Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616086039"
				Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616087089"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)
		end
		coroutine.wrap(LIVE_fake_script)()
		local function PQBDMP_fake_script() -- Pirate.LocalScript 
			local script = Instance.new('LocalScript', Pirate)
	
			script.Parent.MouseButton1Click:Connect(function()
				local Animate = game.Players.LocalPlayer.Character.Animate
				Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=750781874"
				Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=750782770"
				Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=750785693"
				Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=750783738"
				Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=750782230"
				Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=750779899"
				Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=750780242"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)
		end
		coroutine.wrap(PQBDMP_fake_script)()
		local function PIEOA_fake_script() -- Ninja.LocalScript 
			local script = Instance.new('LocalScript', Ninja)
	
			script.Parent.MouseButton1Click:Connect(function()
				local Animate = game.Players.LocalPlayer.Character.Animate
				Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=656117400"
				Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=656118341"
				Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=656121766"
				Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=656118852"
				Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=656117878"
				Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=656114359"
				Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=656115606"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)
		end
		coroutine.wrap(PIEOA_fake_script)()
		local function HCFA_fake_script() -- Mage.LocalScript 
			local script = Instance.new('LocalScript', Mage)
	
			script.Parent.MouseButton1Click:Connect(function()
				local Animate = game.Players.LocalPlayer.Character.Animate
				Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=707742142"
				Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=707855907"
				Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=707897309"
				Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=707861613"
				Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=707853694"
				Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=707826056"
				Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=707829716"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)
		end
		coroutine.wrap(HCFA_fake_script)()
		local function FAQAZUG_fake_script() -- Astronaut.LocalScript 
			local script = Instance.new('LocalScript', Astronaut)
	
			script.Parent.MouseButton1Click:Connect(function()
				local Animate = game.Players.LocalPlayer.Character.Animate
				Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=891621366"
				Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=891633237"
				Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=891667138"
				Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=891636393"
				Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=891627522"
				Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=891609353"
				Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=891617961"
				game.Players.LocalPlayer.Character.Humanoid.Jump = true
			end)
		end
		coroutine.wrap(FAQAZUG_fake_script)()
		local function GIQAC_fake_script() -- close.LocalScript 
			local script = Instance.new('LocalScript', close)
	
			script.Parent.MouseButton1Click:Connect(function()
				script.Parent.Parent.Visible = false
			end)
		end
		coroutine.wrap(GIQAC_fake_script)()
