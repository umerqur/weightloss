# GitHub Pages Deployment Instructions

Your Sherlase Wellness landing page is ready to be deployed! Follow these simple steps to make it live on GitHub Pages.

## 📋 Steps to Deploy

### Option 1: Deploy from Current Branch (Recommended)

1. **Go to your repository on GitHub**
   - Navigate to: `https://github.com/umerqur/weightloss`

2. **Access GitHub Pages Settings**
   - Click on **Settings** (top navigation bar)
   - In the left sidebar, click on **Pages** (under "Code and automation")

3. **Configure the Source**
   - Under "Build and deployment" → "Source", select **Deploy from a branch**
   - Under "Branch":
     - Select: `claude/sherlea-landing-page-01SLVxjBCahURF5yU19mQ2NF`
     - Folder: `/ (root)`
   - Click **Save**

4. **Wait for Deployment**
   - GitHub will automatically build and deploy your site
   - This typically takes 1-3 minutes
   - You'll see a message at the top with your site URL

5. **Access Your Site**
   - Your site will be available at: `https://umerqur.github.io/weightloss/`
   - GitHub will show you the exact URL once deployment is complete

### Option 2: Deploy from Main Branch (Alternative)

If you prefer to use the main branch:

1. **Merge your changes to main**
   ```bash
   git checkout main
   git merge claude/sherlea-landing-page-01SLVxjBCahURF5yU19mQ2NF
   git push origin main
   ```

2. **Follow steps 2-5 from Option 1**, but select `main` as the branch instead

## 🎨 What's Included

Your landing page includes:

- ✅ Responsive design that works on all devices
- ✅ Modern typography (DM Sans & Crimson Pro)
- ✅ Hero section with automatic image slideshow
- ✅ Transparent overlay effects
- ✅ Expert Guidance section with trapezoid overlay
- ✅ Real Results testimonials with enhanced backgrounds
- ✅ Metabolic Balance section with organic background splash
- ✅ Contact form (demo mode - needs backend integration)
- ✅ Smooth scrolling navigation
- ✅ Fade-in animations

## 🔧 Customization

To customize your landing page:

1. **Images**: Replace the Unsplash URLs in `index.html` with your own images
2. **Content**: Edit the text in `index.html` to match your branding
3. **Colors**: Update CSS variables in `style.css` (lines 15-24)
4. **Contact Form**: Integrate with a backend service like Formspree, Netlify Forms, or your own API

## 📝 Custom Domain (Optional)

To use a custom domain like `www.sherlasewellness.com`:

1. In GitHub Pages settings, enter your custom domain
2. Add DNS records at your domain provider:
   - For apex domain (sherlasewellness.com): Add A records to GitHub's IPs
   - For www subdomain: Add CNAME record pointing to `umerqur.github.io`
3. Enable "Enforce HTTPS" in GitHub Pages settings

Full instructions: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## 🚀 Going Live Checklist

Before sharing your site:

- [ ] Test on mobile devices
- [ ] Update contact form to connect to a real backend
- [ ] Replace placeholder images with your actual photos
- [ ] Update contact information in the footer
- [ ] Test all navigation links
- [ ] Add your business logo to the navbar
- [ ] Configure analytics (Google Analytics, etc.)

## 📞 Support

If you encounter any issues:
- Check the Actions tab in your repository for build errors
- Ensure the branch name is spelled correctly in Settings → Pages
- Wait a few minutes after saving settings for changes to take effect

---

**Your landing page is ready to transform your business! 🎉**
