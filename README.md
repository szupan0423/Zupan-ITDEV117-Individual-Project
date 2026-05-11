# Zupan-ITDEV117-Individual-Project
README: 
Drink! App Design Project

Drink!   
Problem the App Solves

In a fast-paced world, people often forget to maintain their physical and mental well-being. Drink! addresses the common issue of dehydration and the lack of mindful breaks during the day. By combining hydration tracking with mandatory breathing exercises, the app helps users combat the negative health effects of constant movement and stress.  
Target Users or Audience

The audience is anyone and everyone. Because hydration and mental resets are fundamental human needs, the app is designed for any individual looking to improve their physical and physical health awareness.  
Key Features of the Application

    Customizable Hydration Goals: Users define a specific daily target for water intake in ounces.  

    Automated Reminders: The system triggers notifications at scheduled times to prompt the user to hydrate.  

    Integrated Mindfulness Timer: Every time water is logged, the app automatically launches a one-minute breathing session.  

    Progress Monitoring: Users can view their current intake against their daily goal at any time.  

    Weekly Tracking: The app employs an array to store daily totals over a seven-day period.  

    Weekly Summary: At the end of the week, the app iterates through the stored data to provide a full hydration report.  

Overview of How the Application Works

The Drink! app operates through a structured interaction between the user and the system:

    Initial Setup: Upon starting the app, the user creates a profile and inputs their daily water goal.  

    Daily Interaction: * The system sends "Time to Drink!" reminders based on a schedule.  

        When the user logs water, the system adds the amount to the currentIntake and immediately triggers the MindfulnessTimer module.  

        The MindfulnessTimer counts down from 1:00 to 0:00, encouraging the user to focus on their breathing.  

    End-of-Day Processing: Once the daily goal is reached, the system saves the total to a weeklyLogArray, resets the daily counter, and moves to the next day.  

    Weekly Conclusion: After seven days of iteration, the app displays a "Weekly Summary" showing the total ounces consumed for each day of the week.  
