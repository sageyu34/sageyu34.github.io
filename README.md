# 🧬 Reproductive Physiology Quiz - GitHub Pages Setup Guide

This guide will help you host your Reproductive Physiology Quiz online for free using GitHub Pages.

## 📦 What You Have

Two files ready for deployment:
1. **index.html** - The enhanced quiz application (much better than the basic ChatGPT version)
2. **reproductive_physiology_question_bank.json** - Your 300 MCQs + 20 essay questions

## ✨ Enhanced Features (vs Basic ChatGPT Version)

My version includes:
- ✅ **Beautiful modern UI** with gradient design and animations
- ✅ **Progress tracking** with visual progress bar
- ✅ **Topic badges** showing which category each question belongs to
- ✅ **Immediate feedback** - know if you're right/wrong instantly
- ✅ **Two quiz modes**: Full quiz (300 questions) or Custom quiz (20 random questions)
- ✅ **Navigation** - go back to previous questions
- ✅ **Detailed results** with score statistics
- ✅ **Review section** showing all incorrect answers with correct answers
- ✅ **Mobile responsive** - works on phones, tablets, and desktops
- ✅ **Error handling** - graceful messages if files don't load
- ✅ **Shuffle/randomization** - questions appear in random order each time

## 🚀 Step-by-Step Deployment Guide

### Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click the **+** icon in the top right corner → **New repository**
3. **Repository name**: Enter `yourusername.github.io` 
   - Replace `yourusername` with your actual GitHub username
   - Example: If your username is `johnsmith`, name it `johnsmith.github.io`
4. **Visibility**: Select **Public** (required for free GitHub Pages)
5. Check **Add a README file**
6. Click **Create repository**

### Step 2: Upload Your Files

**Option A: Drag & Drop (Easiest)**
1. In your new repository, click **Add file** → **Upload files**
2. Drag both files from your computer:
   - `index.html`
   - `reproductive_physiology_question_bank.json`
3. Scroll down and click **Commit changes**

**Option B: Edit & Paste**
1. Click **Add file** → **Create new file**
2. Name it `index.html`
3. Copy and paste the entire HTML content
4. Click **Commit new file**
5. Repeat for `reproductive_physiology_question_bank.json`

### Step 3: Enable GitHub Pages

1. In your repository, click **Settings** (tab at the top)
2. In the left sidebar, scroll down and click **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, select **main** and **/(root)**
5. Click **Save**

### Step 4: Wait & Access Your Site

- ⏱️ **Wait 2-5 minutes** for GitHub to build and deploy your site
- 🌐 Your site will be live at: `https://yourusername.github.io`
- 📱 You can also see the URL in the Settings → Pages section

## 🎯 How to Use the Quiz

Once your site is live:

1. **Visit your site** (e.g., `https://johnsmith.github.io`)
2. **Choose a mode**:
   - **Start Quiz**: All 300 questions in random order
   - **Custom Quiz**: Quick 20-question session
3. **Answer questions**: Click the option you think is correct
4. **Get immediate feedback**: See if you're right and learn the correct answer
5. **Navigate**: Use Previous/Next buttons or wait for auto-advance
6. **Review results**: See your score, accuracy, and review wrong answers
7. **Restart**: Take the quiz again with different random questions

## 🛠️ Customization Options

### Change the Number of Custom Quiz Questions

Edit `index.html` and find this line:
```javascript
questions = shuffleArray(allQuestions).slice(0, 20);
```

Change `20` to any number you want (e.g., 50, 100, 10).

### Change Colors/Theme

In the `<style>` section of `index.html`, look for:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

Change `#667eea` and `#764ba2` to any colors you like. Use [color-hex.com](https://www.color-hex.com) to find colors.

### Add a Custom Domain (Optional)

Instead of `username.github.io`, you can use your own domain:
1. Buy a domain from Namecheap, GoDaddy, etc.
2. In repository Settings → Pages, enter your domain under "Custom domain"
3. Configure DNS with your domain provider (GitHub will show you exactly what to do)
4. Check "Enforce HTTPS" for security

## 📱 Sharing Your Quiz

Once live, share your quiz with:
- Classmates: "Study for the exam at https://yourusername.github.io"
- Teachers: "Interactive quiz for reproductive physiology"
- Study groups: "Test your knowledge with 300+ questions"

## 🔧 Troubleshooting

### Site shows 404 error
- Wait 5 more minutes (GitHub Pages takes time)
- Check that files are in the main branch (not a folder)
- Verify repository is Public

### Questions don't load
- Check that `reproductive_physiology_question_bank.json` is spelled correctly
- Open browser console (F12) to see error messages
- Ensure both files are in the same folder/repository

### Changes not appearing
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Changes can take 2-10 minutes to deploy

## 📊 File Sizes

- `index.html`: ~15 KB
- `reproductive_physiology_question_bank.json`: ~150 KB
- **Total**: Under 200 KB (very fast loading!)

## 🎓 Why This is Better Than ChatGPT's Version

| Feature | ChatGPT Version | My Enhanced Version |
|---------|----------------|---------------------|
| Design | Basic, plain | Modern, beautiful gradients |
| Progress tracking | ❌ None | ✅ Visual progress bar |
| Topic labels | ❌ None | ✅ Shows topic for each question |
| Quiz modes | ❌ One mode | ✅ Full (300) or Custom (20) |
| Navigation | ❌ Forward only | ✅ Previous/Next buttons |
| Feedback | ❌ None | ✅ Immediate correct/incorrect |
| Results | ❌ None | ✅ Detailed score + review |
| Mobile support | ❌ Poor | ✅ Fully responsive |
| Error handling | ❌ Basic | ✅ Graceful error messages |
| Shuffle questions | ✅ Yes | ✅ Yes + better algorithm |

## 📚 Resources

- [GitHub Pages Documentation](https://docs.github.com/pages)
- [Custom Domain Guide](https://docs.github.com/articles/using-a-custom-domain-with-github-pages)
- [Troubleshooting](https://docs.github.com/articles/troubleshooting-jekyll-build-errors-for-github-pages-sites)

---

**🎉 You're all set! Follow the steps above and your quiz will be live in minutes!**

*Created with enhanced features specifically for your Reproductive Physiology Question Bank*
