Magic Studio | Virtual ExperienceA single-page web application that simulates AI-powered image transformation with Disney-inspired styling.🚀 How to Deploy to VercelYou can deploy this application for free in less than 2 minutes.Method 1: Upload via Dashboard (Easiest)Download the index.html file provided above.Go to Vercel.com and log in.Click "Add New" > "Project".Drag and drop the folder containing your index.html file onto the Vercel dashboard.Click Deploy.Method 2: Via GitHub (Recommended for Updates)Create a folder on your computer named magic-studio.Save the index.html file inside that folder.Create a new Repository on GitHub.Push the folder to GitHub:cd magic-studio
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin [https://github.com/YOUR_USERNAME/YOUR_REPO.git](https://github.com/YOUR_USERNAME/YOUR_REPO.git)
git push -u origin main
Go to Vercel, click "Add New Project", and select "Import from GitHub".Select your new repository and click Deploy.🛠 ConfigurationConnecting to Real AI (N8N)By default, the app runs in Demo Mode using CSS filters. To connect it to a real backend:Open index.html.Locate the CONFIG object near line 450.Set useN8n: true.Update n8nWebhookUrl with your actual endpoint.const CONFIG = {
    useN8n: true, 
    n8nWebhookUrl: '[https://your-n8n-instance.com/webhook/](https://your-n8n-instance.com/webhook/)...'
};
✨ FeaturesStep 1: Drag & Drop Image Upload.Step 2: 4 Unique Style Presets (Cartoon, Sketch, Abstract, Noir).Step 3: Real-time Preview with TRON-inspired Magic Frame.Step 4: Share options (Email simulation & QR Code).Download: Auto-composites the frame and filtered image into a single PNG.
